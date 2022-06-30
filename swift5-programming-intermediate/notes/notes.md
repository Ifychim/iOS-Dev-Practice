# **`Swift5 Intermediate Topics:`**

This deep dive covers basic topics of programming with Swift based on **`Swift5`**

-  **`Table of contents`:**
    - IF/ELSE Statements
    - Switch Statements    
    - Dictionaries
    - Optionals(!?)
    - 5 Step Debugging Process

#### **`IF/ELSE Statements`:**
Swift5 provides If-Else statements to help with control flow.

- IF/ELSE Example:
```
if trafficLight == "green" {
    go()
}else if traficLight == "yellow" {
    useYourJudgement()
}else {
    stop()
}
```  

#### **`Switch Statements`:**
Swift5 provides switch statements to help with control flow.

- Switch statement Example:
```
switch trafficLight {
    case "Green":
        go()
        break
    case "Yellow":
        useYourJudgeMent()
        break
    default:
        stop()
        break;
}
```  
    
#### **`Dictionaries`:**
Swift5 provides dictionaries as a method for storing data in key:value pairs
When working with dictionaries important methods to execute are: Retreive elements value by key, Retrieve all values & keys, Update dictionary, Insert entry, Delete entry,

- String Dictionary Examples:
```
//Initialize our dictionary (specifying inference)
var phoneBook : [String:Int] = ["Contact1": 12345,
                                "Contact2": 54321]
                                
//Retrieving value by key
print(phoneBook["Contact1"])

//Updating an existing entry in our dictionary
phoneBook.updateValue(1223, forKey: "Contact1")

//Inserting an entry into our dictionary
phoneBook["Contact3"] = 13579

//Removing an entry from our dictionary
phoneBook.removeValue(forKey: "Contact2")
```    

#### **Optionals(!?)** 
In Swift5 Optionals are variables which might start out containing no data. 
For example, on a sign-in page, the userName field starts out empty but at some point might be filled with relevant data.
In Swift5 nil represents a literal null value for objects.
To unwrap optionals in swift (get their true data type) we can use an exclamation. 

- Optionals Examples:
    - var userName: String? (an optional that holds a string which can be empty(nil) or populated)
    - var userNameUnwrapped: userName! (an unWrapped optional, populated variable)
    
    
```
//userName optional
var userName: String?
userName = "testName"
print(userName) //outputs Optional("testName")

if userName != nil {
    unWrappedName = userName! //executes when user has provided a string as a userName.
    print(unWrappedName) //outputs testName
}
``` 

#### **`5 Step Debugging Process`:**
To generate a random number in Swift5 we tap into the built in "Int/Float/Double" class which provides a random() method.



- Range and Randomization examples:
```Int/Float/Double.random(in:0...5) -> generate a random number in the range from 0-5 upper bound inclusive```  
```Int/Float/Double.random(in:0..<5) -> generate a random number in the range from 0-5 upper bound non-inclusive``` 
```Bool.random() -> returns a random true/false value```
```array.randomElement() -> returns a random element in the array``` 
```array.shuffle() -> returns a random element in the array```



Done!




