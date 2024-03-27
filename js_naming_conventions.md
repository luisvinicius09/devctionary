# JavaScript Coding Conventions

> Source: https://www.w3schools.com/js/js_conventions.asp

Coding conventions are not used by computers. Most rules have little impact on the execution of programs.
Indentation and extra spaces are not significant in small scripts.
For code in development, readibility should be preferred. Larger production scripts should be minimized.

## What you will find here:

- [Naming and declaration rules for variables and function]()
- [Rules for the use of white space, indentation, and comments]()
- [Programming practices and principles]()

### Variable Names

Commonly used is `camelCase` for identifiers names(variables and functions);
All names start with a letter
Ex:

```js
firstName = 'John';
lastName = 'Doe';

price = 19.9;
tax = 0.2;

fullPrice = price + price * tax;
```

Constants (like PI) written in UPPERCASE

### Spaces Around Operators

Always put spaces around operators ( = + - \* / ), and after commas
Ex:

```js
let x = y + z;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

### Code Identation
There is available, tabs and spaces. Always use spaces for indentation of code blocks.
Different editors interpret tabs differently
Ex:
```js
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```


