# Data Structure
## Array
<!-- ![[Pasted image 20221206001855.png]] -->
![](../src/img/Pasted%20image%2020221206001855.png)




Exampls
```python
fruits = ["Apple", "Orange", "Benanana"]
```

## Tuple
<!-- ![[Pasted image 20221216152209.png]] -->
![](../src/img/Pasted%20image%2020221216152209.png)



- but mutable
```python
# Define
fruits = ("Apple", "Orange", "Bananana")
# Lentgh
print(len(fruits))	
# Read
print(fruits[0])
# Assigngit!
fruits[1] = "Watermelone" 
```


## Set
- same as math
```python
names = {"Ahmad", "Ali", "Hamed"}
```


- non ordered
```python
print(names[0])
names[1] = "Mohammad"
```


- non-repetitive
```python
names = {"Ahmad", "Ali", "Hamed", "Ali"}
print(names)
>> names = {"Ahmad", "Ali", "Hamed"}
```

---
## dictionary
- Like dictionary in real world
 <!-- ![[Pasted image 20221216161419.png]] -->

![](../src/img/Pasted%20image%2020221216161419.png)


Example
```python
person = {"first_name":"Ahmad", "last_name":"Sharifianzade", "Age":30, }

print(person)

print(person["last_name"])

person['Age'] = 45
```