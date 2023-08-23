# TypeScript


## TypeScript - Type Annotations

TypeScript is a typed language, where we can specify the type of the variables, function parameters and object properties. We can specify the type using:Type after the name of the variable, parameter or property. There can be a space after the colon. TypeScript includes all the primitive types of JavaScript- number, string and boolean.



`code `

`var age: number = 32; // number variable`
`var name: string = "John";// string variable`
`var isUpdated: boolean = true;// Boolean variable`

## TypeScript Data Type - Number
Just like JavaScript, TypeScript supports number of data types. All numbers are stored as floating point numbers. These numbers can be Decimal (base 10), Hexadecimal (base 16) or Octal (base 8).

`Example ` :
let number :number = 12 ;
let newNumber:number = 15 ;
let myFloatNumber:number = 12.45 ;

console.log(newNumber)
console.log(newNumber.toString());
console.log(newNumber.toPrecision());
console.log(newNumber.toFixed());


## TypeScript - String 
String is another primitive data type that is used to store text data. Single quotation marks or double quotation marks surround string values.

let myFirstName:string = "Ranjana ";
let myLastName:string = " Yadav";

let myFullName :string = myFirstName+ myLastName;
console.log(myFullName)







