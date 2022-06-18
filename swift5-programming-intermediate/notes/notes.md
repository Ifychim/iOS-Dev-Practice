# **`Swift5 Intermediate Topics:`**

This deep dive covers basic topics of programming with Swift based on **`Swift5`**

-  **`Table of contents`:**
    - Control Flow and Optionals
    - Commenting
    - String Interpolation    
    - Variables and Arrays
    - Constants
    - Range Operator and Randomization.

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



Done!




