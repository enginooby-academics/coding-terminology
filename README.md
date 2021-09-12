# Typing
### Structurally typed _[TS]_  
+ Allow instances of a type to have **_extra properties_**
```ts
interface User {name: string; age: number}

const jeff = {name: 'Jeff', age: 18, gender: 'male'}; 
const user: User = jeff; // OK
```

### Statically typed _[C/C++, C#, Java, Kotlin, TS, Scala, Rust, Go]_
+ Variable types are _**determined at compile time**_, either by type annotation or type inference
```csharp
string name = "Jeff";  // type annotation
var name = "Jeff"; // type inference
```

+ Determine _**allowed operations**_ on the variables
```csharp
const a = name / 3; // Compile error
const a = name + "Bezos"; // OK
```


# Data Structure
### Tuple _[Python, C#7]_
+ Characteristics:  
  - _**Immutable**_: size is fixed and elements can not be modified => less memory and iterate faster than list, array,
  - Can contain elements of _**different data types**_.
  - Operations: _**indexing**, **slicing**, **membership test**_.
+ Use cases:
  - Return multiple values from private and internal utility methods w/o define a new type (POCO class/interface...)
  - Asign multiple variables at the same time.
  - Swap two variables w/o using additional temprory variable.



# Others
### First class citizen
An entity which supports all the operations generally available to other entities, such as _**being passed as an argument**, **returned from a function**, **modified**, **assigned to a variable**._

### First class function _[JS/TS, Dart, Kotlin, Scala, Swift, Rust]_
+ Treat function as first class citizen -> can be passed as an argument
+ The argument function can be a _**ananymous function**_
+ Use cases:
  - Callback
  - Used along w/ collection operations such as map(), where(), and reduce(), etc
