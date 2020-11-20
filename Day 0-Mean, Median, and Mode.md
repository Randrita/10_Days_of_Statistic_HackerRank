```python
print("Enter the number to check its mean,median nd mode:")
numbers=list(map(int,input().split()))
```

    Enter the number to check its mean,median nd mode:
    1 3 2 4 4
    


```python
print(numbers)
length_of_array= len(numbers)
print(length_of_array)
```

    [1, 3, 2, 4, 4]
    5
    


```python
#mean
count=0
for i in numbers:
    count=count+i
print("total of all numbers is",count)
    
```

    total of all numbers is 14
    


```python
print("the mean of the numbers is:",(count/length_of_array))
```

    the mean of the numbers is: 2.8
    


```python
#median
sorted_list= numbers.sort()
```


```python
print(numbers)
```

    [1, 2, 3, 4, 4]
    


```python
if length_of_array % 2 ==0:
    m = numbers[length_of_array//2]
    m2=numbers[length_of_array//2+1]
    median=(m+m2)/2
else:
    median=(numbers[length_of_array//2])
print(median)
```

    3
    


```python
#mode
from statistics import mode
```


```python
mode=mode(numbers)
```


```python
print(mode)
```

    4
    


```python

```
