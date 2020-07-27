```python
list1 = [1,2,3,4,5,6,7,8]
list2 = ["a","b","c","d","e"]
dict1 = {}
length = min(len(list1), len(list2))
for each in range(min(len(list1), len(list2))):
    dict1.update(list1[each]) = list2[each]
    
print(dict1)
```

    {1: 'a', 2: 'b', 3: 'c', 4: 'd', 5: 'e'}
    


```python
print ({list1[each]:list2[each] for each in range(length)})
```

    {1: 'a', 2: 'b', 3: 'c', 4: 'd', 5: 'e'}
    


```python

```


```python

```
