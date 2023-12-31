# Module 2: Variables / Data
### What's Covered?
- Creating variables
- Types of variables
- Changing types
- Editing variables
- Printing

### Creating Variables
In python, creating variables are pretty straight forward.  
  
What is on the __left__ of the `=` will be the variable name.  
What is on the __right__ of the `=` will be what is stored inside the variable.

For example, you want to name a variable `x`, and store the number `8` inside of it. You would do `x = 8`.  

**Python Variable Naming Rules:**
- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)

### Types of Variables
There are different types of variables meant to store different types of data.
- Numbers
  - Integers (1, 2, 3)
  - Floats (1.0, 2.0, 3.25)
- Text
  - Strings ("Hello!", "(598dshfkweq)", "Pyth0n ru13z")
- Lists ([1, 2, 3], ["Apple", "Banana", "Mango"])
- Tuples ("Apple", "Banana"), ("Cheese", "Pizza") (1, 3, 5)

### Variables in use
```
integerVar = 28
floatVar = 4.0
stringVar = "Hello World!"
listVar = [1, 2, 3]
tupleVar = (1, 2, 3)
```

### Changing Types
To an extent, you can change different variable types. Like converting an int to a string, or an int to a float. 
- int()
- float()
- str()
- list()
- tuple()

For example, let's convert the number `1822` into a string:
```
x = 1822 # Currently an integer
x = str(x) # Converted to a string
```

### Editing Variables
You can also edit variables throughout your program.  
You can start with a variable called `x`, then edit `x` as you go on, by re-declaring it.  
  
Example:
```
x = 124
# Add more code here
x = 124 + 2

print(x) # Will output 126
```

### Printing Variables
You can print variables like any normal print.

Example:
```
varInt = 45
varStr = "Hello!"
varTable = [1, 2, 3]

print(varInt) ## Outputs 45
print(varInt + 2) ## Outputs 47

print(varStr) ## Outputs Hello!
print(varStr + "!!") ## Outputs Hello!!!

print(varTable) ## Outputs [1, 2, 3]
```
