
length=100
breadth=100
print(id(length),id(breath))

we see both printing same memory location , means both length and breadth are pointing to same location



## DataType

1. int = any -ve or +ve value
2. string="Abhay"
3. float = decimal value
4. Boolean = True,False


type(name_of_variable) -> gives the type of the variable


**Escape Seq**
print("My name is \"Abhay\" here")
\t -> 4 space 


##### String formatting
2 ways of string formatting:
1. fstring
2.  .format()
```python
year = 2016
event = 'Referendum'
f'Results of the {year} {event}'

o/p: - 'Results of the 2016 Referendum'
```

.format example
```python
print('We are the {} who say "{}!"'.format('knights', 'Ni'))
o/p: We are the knights who say "Ni!"
```

# Logging 
1. You can use the library **loguru**
```python
from loguru import logger
 logger.info(print(f'Results of the {year} {event}'))
```


Operator

1.  division
	```python
	print(15/6)
	output:2.5
	```
2. floor division
```python
-- discards the value after decimal
print(15//6)
output : 2
```

TypeError
```python
a="12"
b=22
print(a+b)
-- will give a type error 'string'+'integer'
```
typecasting
```python
a="12"
b=22
print(int(a)+b)
output - 34
```
str( ) -> to typecast to string

### Types of typcasting
1. Explicit typecasting
2. Implicit typecasting

### Where is if else used?
1. check whether variable or list is not empty
2. check if dataframe is not empty
3. Backdated job run
4. To raise some error


