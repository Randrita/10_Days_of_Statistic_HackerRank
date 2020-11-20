```python
print("Enter the number of elements:")
n=int(input())
w=list(map(int,input().split()))
x=list(map(int,input().split()))
```

    Enter the number of elements:
    3
    5 10 15
    50 75 100
    


```python
print(w)
```

    [5, 10, 15]
    


```python
count=0
for i in w:
    count=count+i
count1=0
for y in x:
    count1=count1+y
weighted_mean= (count*count1)/count
```


```python
print(weighted_mean)
```

    225.0
    


```python

```
