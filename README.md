# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 


`.map` - creates a new array with converted data from a provided function without manipulating the original array. A return statement must be used.
Use: It used to invoke a function on every element in an array (e.g. the .toLowerCase() function can be used with .map to convert all capital lettters in an array to lowercased letters).

`.filter` - creates a new array with all elements that pass a test implemented by a provided function without manipulating the original array. A return statement must be used. 
Use: It is used to filter out certain wanted results into a new array that can pass a true or false test (e.g. if a test passes as true, its included in the new array, if it fails as false it's not included in the new array). )

`.reduce` - does NOT create a new array and only returns a single value after it's run across all elements. It does not manipulate the original array and it could be used for anything. 
Use: It is usually used for addition and multiplication.


2. Explain the difference between a callback and a higher order function.


Higher Order Functions can receive other functions as parameters. 
Callback Functions can be passed into other functions as arguements.
(i.e. A Callback Function can be passed into a High Order Function.)


3. Explain what a closure is.


Closure is when an inner function has to reach outside of its scope to grab a variable defined in the outer scope becuase the variable is not defined in the inner function's scope.


4. Describe the four principles of the 'this' keyword.


 (1) Window Binding - when "this" is in the global scope, the value of "this" will be the window or console object (global object in node or undefined in strict mode).

 (2) Implicit Binding - the value of "this" is the object to the left of a dot when using dot notation to invoke a function (method). This only applies to objects with methods.

 (3) New Binding - the value of "this" is the object that is created and returned by the constructor function during a specifc instance, when using constructor functions.
 
 (4) Explicit Binding - the value of "this" is the new/other object that is explicitly defined when using the .call, .apply or .bind method.
  

5. Why do we need super() in an extended class?


We need super() in an extended class becuase it tells a parent's constructor to be concerned with the child's attributes.


You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

