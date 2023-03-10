Answer to question 1. symbols for each of the Javascript operators

// symbols for Arithmetic Operator
+, -, *, /, %, **, ++, --

// symbols for Assignment Operator
=, +=, -=, *=, /=, %=

// symbols for Comparison Operator
==, ===, !=, !==, >, >=, <, <=,

// symbols for Logical Operator
&&, ||, !

// symbols for Biwise Operator
&, |, ^, ~, <<, >>, >>>

Answer to Question 2. Two examples of each JavaScript Operator.

// Arithmetic Operator

const sum =50 + 25;
console.log(sum);
Answer is 75

const minus = 30 - 20;
console.log(minus);
Answer is 10

const multiply = 50 * 2;
console.log(multiply);
Answer is 100

const divide = 50 / 25;
console.log(divide);
Answer is 2

const remainder = 505 % 2;
console.log(remainder);
Answer is 1

let sum2 = 20 + 20;
console.log(sum2);
Answer is 40

sum2++;
console.log(sum2);
Answer is 41

sum2--;
console.log(sum2);
Answer is 40


// Assignment Operator

let num1 = 50;
num1 = num1 + 20;
console.log(num1);
Answer is 70

num1 += 20;
console.log(num1);
Answer is 90

num1 -= 30;
console.log(num1);
Answer is 60

let num2 = 40;
num2 *= 2;
console.log(num2);
Answer is 80

let num3 = 40;
num3 /= 3;
console.log(num3);
Answer is 13.333333333333334

let num4 = 400;
num4 %= 3;
console.log(num4);
Answer is 1


// Comparison Operator

Let equal = 630 == 400;
console.log(equal);
Answer is false

Let equal2 = 100 == 100;
console.log(equal2);
Answer is true

let equal3 = '50' === 50;
console.log(equal3);
Answer is false

let equal3 = '30' === '30';
console.log(equal3);
Answer is true

let notEqual = 20 != 10;
console.log(notEqual);
Answer is true

let greater = 90 > 60;
console.log(greater);
Answer is true

Let greaterEqual = 50 >= 50;
console.log(greaterEqual);
Answer is true

let less = 20 < 5;
console.log(less);
Answer is false

let lessEqual = 10 <= 10;
console.log(lessEqual);
Answer is true


// Logical Operator

let and1 = (50 < 20 && 20 < 30 );
console.log(and1);
Answer is false

let and2 = (10 < 20 && 20 < 30 );
console.log(and2);
Answer is true

let or = (10 < 20 || 20 < 30 );
console.log(or);
Answer is true

let not = !(10 < 20 || 20 < 30 );
console.log(not);
Answer is false


// Biwise Operator

let bitAnd = (10 == 20 & 20 == 33);
console.log(bitAnd);
Answer is 0

let bitAnd = (10==10 & 20 == 20);
console.log(bitAnd);
Answer is 1

let bitOr = (10==10 | 20 == 20);
console.log(bitOr);
Answer is 1

let bitOr = (10==20 | 20 == 33);
console.log(bitOr);
Answer is 0

let bitNot = ~9;
console.log(bitNot);
Answer is -10

let bitLeftShift = 30<<2;
console.log(bitLeftShift);
Answer is 120

let bitRightShift = 30>>2;
console.log(bitRightShift);
Answer is 7

let bitRightShiftWithZero = 30>>>2;
console.log(bitRightShiftWithZero);
Answer is 7


// Answer to question 5

for (let i = 1; i < 20; i += 7) {
    console.log(i);
}
Answer is
1
8
15# JavaScript-Operators-and-control-flow
