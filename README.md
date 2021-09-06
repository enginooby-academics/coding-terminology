# Coding Terminologies

+ **Structurally typed**: allow instances of a type to have extra properties _[TS]_
```
interface User {name: string; age: number}

const jeff = {name: 'Jeff', age: 18, gender: 'male'}; 
const user: User = jeff; // OK
```
