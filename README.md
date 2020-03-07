# TypeScript-basics
Contains basic type Script theory

## **TypeScript**
```
TypeScript is a superset to JavaScript, which means, that it compiles into pure JavaScript in the end.
```
>First, it provides `strong typing` (that’s where the name comes from).

This means that we can(and should) assign types to our variables and class members. These types won’t compile to
JavaScript (as JS does not know types) but we will get compilation errors if we assign wrong types or make any 
other type-related errors.

TypeScript introduces some nice features, JS does not have out of the box (at least
in the ES5 specification). This includes classes (‘class’ keyword), interfaces, generics and
modules. Being able to use these constructs makes our code cleaner, easier to read and
helps us avoid nasty errors.

Angular using plain JavaScript is extremely hard. And to be honest: TypeScript will be the
standard ‘language’ to be used when developing Angular 2 applications. So I definitely
recommend using TypeScript

## ***USing Types***
 TypeScripts - well - `strong typing allows us to define types for our variables and class members`
 >The compiler is going to tell us if we assign a value of a wrong type to such a variable or member
 
 ### Declaring a variable with a type
Using the `let` keyword to create a variable (`const` would define an immutable constant)
```
let jString: string;

jString = 'This is a string';
```
>No Error

Instead of String try to assign a number to a string then there will be an Error
```
jString = 4;
```
>Error: Type '4' is not assignable to type 'string'.

