# Sum of n numbers 


```python
num = int(input('Enter a number :'))
count = 1
sum = 0
while count <= num :
    sum = sum + count
    count= count + 1
print(f'Sum of first {num} number is {sum}')
```

    Enter a number :10
    Sum of first 10 number is 55
    

# Find if whether the number is prime number or not


```python
n = int(input("Enter a number: "))
r_n = int(n ** 0.5); i = 2;
flag = 0
while i <= r_n :
    if n % i == 0:
        flag = 1
        break
    i += 1
if flag:
    print("Number is a not Prime number")
else:
    print('Number is prime')
```

    Enter a number: 45
    Number is a not Prime number
    


```python
n = int(input("Enter a number: "))
r_n = int(n ** 0.5); i = 2;
flag = 0
while i <= r_n :
    if n % i == 0:
        flag = 1
        break
    i += 1
if flag:
    print("Number is a not Prime number")
else:
    print('Number is prime')
```

    Enter a number: 11
    Number is prime
    


```python

```
