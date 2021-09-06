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

