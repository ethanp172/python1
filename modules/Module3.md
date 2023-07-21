# Module 3: Functions
### What's Covered?
- Creating functions
- Using functions
- Function Examples

### Creating Functions
You can create a function by declarding it using `def`, then the function name, followed by any parameters you will need.  

Parameters are things you can give the function to work with, like a variable just for the function. If you have nothing to intake, add nothing in the `()`. If you want to intake several parameters, seperate them by commas, like `(x, y, z)`.

Here is an example for making a basic function:
```
def myFunctionNameWithNoParams():
    # Function Code

def myFunctionNameWithSomeParams(x, y, z):
    # Function Code
```

Python uses **white space** insead of curly braces like other languages use. After a functon or conditional that uses several lines, you will add a `:` to the end of your top line, then every line below you want to use, add an `indent`. 


### Running Functions
You can run a function by typing the function name, followed by any parameters.  
Example:
```
myFunctionNameWithNoParams()

myFunctionNameWithSomeParams(1, 2, 3)
```

### Function Examples
Let's create a function that prints hello world.
```
def helloWorldFunction():
    print("Hello World!")

helloWorldFunction()
```
Output:  
> Hello World!

<br>

Now, let's create a function that will take in `2` numbers, and will output the `sum` of those 2 numbers.
```
def additionFunction(x, y):
    print(x + y)

additionFunction(5, 4)
```
Output:
> 9


