## Strawberry
The official repo for the Strawberry language

### Simple example
```lua
use System;

type Gender int;

const Male: Gender = 0;
const Female: Gender = 1;

type Person struct {
    Name: string,
    Age: int,
    Gender: Gender
}

met Main (): none {
    System.println ("Hello, World!");

    John: Person = Person { Name: "John Doe", Age: 38, Gender: Male };
    System.println (John.Gender);
}
```
