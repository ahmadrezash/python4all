# Module and Packages
## Module
### Define
- Save this code in a file named `mymodule.py`
```python
def greeting(name):  
  print("Hello, " + name)
```
- use this code in file named `main.py`
```python
import mymodule  
  
mymodule.greeting("Ahmad")
```
---
### Naming
```python
import mymodule as module1
  
module1.greeting("Ahmad")
```
----
### Import func from module
```python
from mymodule import greeting
  
Python Pickle is used to serialize and deserialize a python object structure.greeting("Ahmad")
```

---

## Package

![[Pasted image 20221217091334.png]]
---
### mod1.py
```python
def foo():
    print('[mod1] foo()')

class Foo:
    pass
```

### mod2.py
```python
def bar():
    print('[mod2] bar()')

class Bar:
    pass
```
---

### usage
```python
import pkg.mod1, pkg.mod2
pkg.mod1.foo()
x = pkg.mod2.Bar()
print(x)
```
---

or

```python
from pkg.mod2 import Bar as Qux
x = Qus()
print(x)
```

---
### Big package
```
![[Pasted image 20221217091712.png]]