# Index of a repeated string


```python
str = "what we think we become, we are python programmers"
temp = str
idx = 0
for each in range(0, str.count('we')):
    if each == 0:
        idx = idx + temp.find('we')
    else:
        idx = idx + temp.find('we') + len('we')
    print(idx)
    temp = str[idx + len('we'):]
```

    5
    14
    25
    

# Exercise 


```python
str.isupper()
```




    False




```python
str.islower()
```




    True




```python
"Hello".islower()
```




    False




```python
"Hello".isupper()
```




    False



islower() method - Return True if the string is a lowercase string, False otherwise.
isupper() method - Return True if the string is an uppercase string, False otherwise.


```python

```
