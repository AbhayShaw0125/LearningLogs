
## 1. Function which do not have return statement python returns special object **None**

## 2. Passing variable no of argument
```python
def sum(*a):  
    sum=0  
    for i in a:  
        sum+=i  
    return sum  
  
print(sum(3,4,5,6))
```

## Does not allow function with no body
```python
def nothing():
	pass
```
