# Typing
### **Structurally typed** _[TS]_  
Allow instances of a type to have extra properties
```
interface User {name: string; age: number}

const jeff = {name: 'Jeff', age: 18, gender: 'male'}; 
const user: User = jeff; // OK
```



# Data Structure
### **Tuple** _[Python, C#7]_
+ Characteristics  
  - **Immutable**: size is fixed and elements can not be modified => less memory and iterate faster than list, array,
  - Can contain elements of **different data types**.
  - Operations: **indexing**, **slicing**, **membership test**.
+ Use cases
  - Return multiple values from private and internal utility methods w/o define a new type (POCO class/interface...)
  - Asign multiple variables at the same time.



# Others
### First class citizen
An entity which supports all the operations generally available to other entities, such as **being passed as an argument**, **returned from a function**, **modified**, and **assigned to a variable**.
### First class function _[JS/TS, Dart, Kotlin, Scala, Swift, Rust]_
+ Treat function as first class citizen -> can be passed as an argument
+ The argument function can be a **ananymous function**
+ Use cases
  - Callback
  - Used along w/ collection operations such as map(), where(), and reduce(), etc
