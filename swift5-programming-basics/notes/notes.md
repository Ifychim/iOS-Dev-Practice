# **`Swift5 Basic Topics:`**

This deep dive covers basic topics of programming with Swift based on **`Swift5`**

-  **`Table of contents`:**
    - Naming Conventions
    - Commenting
    - String Interpolation    
    - Variables and Arrays
    - Constants
    - Range Operator and Randomization.
    - Functions and Inference
    - 5 step process to solve programming problems in Swift5

#### **`Naming Conventions`:**
In Swift5 `camelCasing` is the conventional method for naming variables and functions.

- camelCasing Examples:
    - weak var userNameVariable;
    - func actionButtonFunction();

#### **`Commenting`:**
There are two types of method for commenting out code Swift5 (Single-Line comments, Multi-line Comment). 

- Commenting Examples:
    - To invoke a single-line comment we use '//' two forward-slashes.
    - To invoke a single-line comment on a line you can use the command 'cmd + /' on the line you wish to comment out.
    - To invoke a multi-line comment we use '/* */' forward slash and asterik.
    
#### **`String Interpolation`:**
String interpolation allows us to input bits of code between bits of text.

- String Interpolation Examples:
    - To invoke string interpolation we use '\()' back-slash followed by a set of parenthesis.
```
//This prints the addition of two integers in-between a string 
print("Two plus three is equals to \(2+3)")
```    


#### **Variables and Arrays** 
In Swift5 we use the 'var' keyword to create variables.
In Swift5 we use the 'let' keyword to create constants.

In Swift 5 we use square brackets to initialize an array.
To access array elements we use indexing.

- Variable and array Examples:
    - var x = 5. -> Variable x with 5 as its value.
    - let x = 5. -> Constant x with 5 as its value.
    - var arr = [1,2,3] -> Variable arr that stores 3 elements (1,2,3).
    - var arr_at_zero = arr[0]
    
    
```
Code Block
``` 

#### **`Range Operator and Randomization`:**
To generate a random number in Swift5 we tap into the built in "Int/Float/Double" class which provides a random() method.



- Range and Randomization examples:
```Int/Float/Double.random(in:0...5) -> generate a random number in the range from 0-5 upper bound inclusive```  
```Int/Float/Double.random(in:0..<5) -> generate a random number in the range from 0-5 upper bound non-inclusive``` 
```Bool.random() -> returns a random true/false value```
```array.randomElement() -> returns a random element in the array``` 
```array.shuffle() -> returns a random element in the array```

#### **Functions and inference** 
In Swift5 we can create functions using the 'func' keyword followed by the function name, parentheses and curly brackets
There are a few important things to take note of when using functions in swift.
1 - How to declare and call void functions
2 - How to declare and call void functions with parameters
3 - How to declare and call non-void functions with parameters
4 - How to declare and call non-void functions with default parameters

- Functions and Respective Syntax Examples:

```
//Declaring and calling Void Functions

func greeting1(){
    print("hello")
}
print(greeting1())

//Declaring and calling Void Functions with Parameters

func greeting2(userName: String) {
    print("hello \(userName)")
}
print(greeting2(userName: "Uchenna Chima 1"))

//Declaring and calling non-void Functions with Parameters 

func greeting3(userName: String) -> String{
    return("hello \(userName)")
}
print(greeting3(userName: "Uchenna Chima 2"))

//Declaring and calling non-void Functions with Default Parameters
func greeting4(userName: String = "Uchenna") -> String{
    return("hello \(userName)")
}
print(greeting4())

``` 
By default, Swift5 infers the data type based on the value given to the variable when declared. E.G var x = 5, variable "x" will be infered to be of type "Int"
To override Swift5's default inference we can use a colon to specifiy datatype. var x: Int = 5


#### **`5 step process to solve programming problems in Swift5`:**
Below is a simple 5 step process to solve most programming problems in Swift5. 
Please note that this process may not always work thus you must tweak it to what works best for you and the problem you are trying to solve.

- 5 step process:
    - Google the question you are trying to solve. A simple google query is given below 
        - <What do you want your app to do? (play sound)> + <Which programming language? (Swift5, e.t.c)> + <Which resource? (Stack Overflow, Official Docs, e.t.c)>
    - Stack OverFlow
        - Once you have gotten to a viable Stack Overflow link, look for the solution which most likely matches your problem ().
    - Implement
        - Implement the Stack Overflow solution in your code.
    - Official Documentation
        - Understand the code in depth by reading the documentation
    - Customization
        - Customize and optimize the code from stack over flow as it may contain bits and pieces which are not relevant to what is needed to solve your problem.
    
    
Done!




