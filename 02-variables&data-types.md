# variables: #

- variable is a place which a value is stored.

- a = 10 (where 10 is the value and a is the variable so the value is stored in a which makes it a variable)

- variables cane be declared as:
   
   ```
   name = "string"
   a = 1
   user_name = "Ravi"
   ```
- variables cannot be declared as:
  
 ```
 - should not be start with a digit.
 - should not be start with symbol.
 - dont use keywords as variables.
 ```

 # DataTypes: #

 - DataTypes means the data which is in which type.

 - There are three datatypes:

   ```
   - Numeric :  Integer,float,Complex
   - Boolean DataType
   - Mapping :  Dictionary
   - Set DataType
   - Sequence : List,Tuple,String
   ```

## Numeric: ##

1. **Integer**:

- 1,2,3,4 --> integers

2. **Float**:

- 1.6,7.8 --> float

3. **complex**:

- 3+2j --> complex  


## Mapping: ##

1. **Dictionary**:

- {} -> dictionary


## Sequence: ##

1. **list**:

- []

2. **Tuple:**

- ()

3. **Set:**

- {}

4. **String**:

- " ",''

5. **Boolean**:

- true , false


## Type Conversion: ##

- converting of one data type to amother data type.

**examples:**

```python

b = 2.9
c = int(b)
print(c)   // returns 2 only
```

```python

a = 2.9
b = int(a)
print(type(b))  // returns int type
```

```python

b = "ravi"
c = int(b) // didnot convert to int
```

```python

b = 10
c = str(b)
print(c)  // '10'
print(type(c)) // returns str
```