1. what is javascript
Ans: Javascript is a popular Programming language
It is known as the language of web
javacsript is used to  create dynamic and interactive websites

2.Variable and types
Ans: there are three types in variables
var 
let 
const

let userAge =21;
let userName ="Dhirubhai"
console.log("Name:"+userName + "Age:"+userAge);

3.Multiline comments 
/*
This function named 'calculateSum' takes two numerical arguments: num1 and num2.
It returns the sum of these two numbers.
The purpose of this function is to perform a basic arithmetic operation (addition)
and return the result to be used in other parts of the code.
*/

function calculateSum(num1, num2) {
    return num1 + num2;
}

console.log(calculateSum(10, 15));
o/p 25

4.Create two variables
let num1=14;
let num2=5;
console.log(num1+num2);
console.log(num1-num2);
console.log(num1*num2);
console.log(num1/num2);

5.Datatypes
//Strings
let myName ="Dhanush";
console.log(myName);

//Integer
let myNumber =21;
console.log(myNumber);

//Boolean
let myBoolean =true;
console.log(myBoolean);

//Array
let myArray =[1,"Apple",false,3.14];
console.log(myArray);

6.Functions
function greetUser(name){
    return "Hello"+name+"! welcome to our company";
}
console.log(greetUser("Dhirubhai"));

7.If else statement
let temperature =50;
if(temperature >=30){
    console.log("Temperature is high");
}else{
    console.log("Temperature is Low");
}

8.For Loop
for(let i=0; i<=5; i++){
    console.log(i);
}

9.Loose equality vs Strict equality
Loose equality
it does not considers about the datatype
let a=30;
let b="30";
console.log((a==b));
Strict Equality
It considers about the datatype and notices it
let a=30;
let b="30";
console.log((a===b));
