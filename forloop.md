```python
#Using for loop
color = ["purple", "pink", "blue"]
for x in color:
  print(x)
```

    purple
    pink
    blue
    


```python
for x in "purple":
  print(x)
```

    p
    u
    r
    p
    l
    e
    


```python
#Using break statement
color = ["purple", "pink", "blue"]
for x in color:
  print(x)
  if x == "pink":
    break
```

    purple
    pink
    


```python
#Using if statement
a= 20000
b = 20000000
if b > a:
  print("b is greater than a")
```

    b is greater than a
    


```python
#Using elif keyword
a = 56
b = 58
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
```

    b is greater than a
    


```python
#Using else keyword
a = 500
b = 1330
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")

```

    b is greater than a
    


```python
a=SHREE
b=SHREE
if b==a:
    print(" equal equal")
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    <ipython-input-13-ca93e0ae11c3> in <module>
    ----> 1 a=SHREE
          2 b=SHREE
          3 if b==a:
          4     print(" equal equal")
    

    NameError: name 'SHREE' is not defined



```python
#Using and keyword
a = 200
b = 33
c = 500
if a > b and c > a:
  print("Both conditions are True")
```

    Both conditions are True
    


```python
days=["sunday","monday","tuesday","wednesday","thursday","friday","saturday"]
for x in days:
    print(x)
```

    sunday
    monday
    tuesday
    wednesday
    thursday
    friday
    saturday
    


```python
weeks=['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday']

for x in weeks:
    if x=='Monday':
     continue
    print(x)


```

    Sunday
    Tuesday
    Wednesday
    Thursday
    Friday
    Saturday
    


```python
weeks=['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday']

for x in weeks:
    if x=='Sunday':
     continue
    if x=='Monday':
     continue
    if x=='Tuesday':
     continue
    if x=='Saturday':
     continue
    print(x)


```

    Wednesday
    Thursday
    Friday
    


```python
weeks=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']

for x in weeks:
    if x=='Sunday':
     print('There will be no AI and ML class in Sunday')
     continue
    if x=='Monday':
     print('There will be no AI and ML class in Monday')   
     continue
    if x=='Tuesday':
     print('There will be no AI and ML class in Tuesday')   
     continue
    if x=='Saturday':
     print('There will be no AI and ML class in Saturday')   
     continue
    print(x)
```

    There will be no AI and ML class in Monday
    There will be no AI and ML class in Tuesday
    Wednesday
    Thursday
    Friday
    There will be no AI and ML class in Saturday
    There will be no AI and ML class in Sunday
    


```python

```
