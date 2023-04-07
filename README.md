# Javsacript
Q#1:Write a JavaScript program that accepts two numbers in two prompts and displays the larger one in the console.
let firstNumber = prompt("Enter the first number:");
let secondNumber = prompt("Enter the second number:");

if (firstNumber > secondNumber) {
  console.log("The first number is larger: " + firstNumber);
} else if (secondNumber > firstNumber) {
  console.log("The second number is larger: " + secondNumber);
} else {
  console.log("The two numbers are equal: " + firstNumber);
}
Q#2:Write a JavaScript conditional statement to find the sign of a number. Display an alert box with the specified sign
let num = prompt("Enter a number:");

if (num > 0) {
  alert("The number is positive.");
} else if (num < 0) {
  alert("The number is negative.");
} else {
  alert("The number is zero.");
}
Q#3: Write a JavaScript program that accepts five numbers in five prompts and displays the larger one in the console.
let num1 = prompt("Enter the first number:");
let num2 = prompt("Enter the second number:");
let num3 = prompt("Enter the third number:");
let num4 = prompt("Enter the fourth number:");
let num5 = prompt("Enter the fifth number:");

let largestNum = num1;

if (num2 > largestNum) {
  largestNum = num2;
}

if (num3 > largestNum) {
  largestNum = num3;
}

if (num4 > largestNum) {
  largestNum = num4;
}

if (num5 > largestNum) {
  largestNum = num5;
}

console.log("The largest number is: " + largestNum);

Q#4: Write a JavaScript for loop that will iterate from 0 to 15. For each iteration, it will check if the current number is odd or even, and display a message to the screen.
for (let i = 0; i <= 15; i++) {
  if (i % 2 === 0) {
    console.log(i + " is even");
  } else {
    console.log(i + " is odd");
  }
}

Q#5: Write a JavaScript program which computes the average marks of the following students Then, this average is used to determine the corresponding grade
// Define the student marks as an array
let marks = [80, 75, 92, 87, 63];

// Compute the sum of the marks
let sum = 0;
for (let i = 0; i < marks.length; i++) {
  sum += marks[i];
}

// Compute the average mark
let average = sum / marks.length;

// Determine the corresponding grade
let grade;
if (average >= 90) {
  grade = "A";
} else if (average >= 80) {
  grade = "B";
} else if (average >= 70) {
  grade = "C";
} else if (average >= 60) {
  grade = "D";
} else {
  grade = "F";
}

// Display the average mark and corresponding grade in the console
console.log("The average mark is: " + average.toFixed(2));
console.log("The corresponding grade is: " + grade);
