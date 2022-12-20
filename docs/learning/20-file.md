# File
## Raw txt
### Openning mode
>`"r"` - Read - Default value. Opens a file for reading, error if the file does not exist
>
>`"a"` - Append - Opens a file for appending, creates the file if it does not exist
> 
> `"w"` - Write - Opens a file for writing, creates the file if it does not exist
> 
> `"x"` - Create - Creates the specified file, returns an error if the file exists 

### Open file
```python
file = open("demofile.txt","r")
print(file.read())
```

## Json
<!-- ![[Pasted image 20221217082534.png]] -->
![](../src/img/Pasted%20image%2020221217082534.png)


### Load json
```python
import json  
  
# some JSON:  
x =  '{ "name":"Ahmad", "age":30, "city":"Tehran"}'  
  
# parse x:  
y = json.loads(x)  
  
# the result is a Python dictionary:  
print(y["age"])
```


### Dump json
```python
import json  
  
# a Python object (dict):  
x = {  
  "name": "Ahmad",  
  "age": 30,  
  "city": "Tehran"  
}  
  
# convert into JSON:  
y = json.dumps(x)  
  
# the result is a JSON string:  
print(y)
```

### With file
```python
import json  
  
# a Python object (dict):  
x = {  
  "name": "Ahmad",  
  "age": 30,  
  "city": "Tehran"  
}  

outfile = open("sample.json", "w")

# save on file
y = json.dump(x, outfile)  
```


## Pickle
- Python Pickle is used to `serialize` and `deserialize` a python object structure.
...
