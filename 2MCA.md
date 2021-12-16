```python
import cv2

 
```


```python
im=cv2.imread('purple.png')

```


```python
cv2.imshow('aaa',im)
cv2.waitKey(0)
cv2.DestroyAllWindows()
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    <ipython-input-3-2f00f7689dea> in <module>
          1 cv2.imshow('aaa',im)
          2 cv2.waitKey(0)
    ----> 3 cv2.DestroyAllWindows()
    

    AttributeError: module 'cv2' has no attribute 'DestroyAllWindows'



```python
colors = im.getpixel((320,240))
```


```python
img {
  -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
  filter: grayscale(100%);
}
```


```python


```


```python

```


```python

```


```python
# Python program to explain cv2.imshow() method

# importing cv2
import cv2

# path
path =  r'E:\Shree\purple.png'


# Reading an image in default mode
image = cv2.imread(path)

# Window name in which image is displayed
window_name = 'Image'

# Using cv2.imshow() method
# Displaying the image
image=cv2.cvtColor(image,cv2.COLOR_BGR2HSV)
cv2.imshow(window_name, image)

#waits for user to press any key
#(this is necessary to avoid Python kernel form crashing)
cv2.waitKey()

#closing all open windows
cv2.destroyAllWindows()
```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
