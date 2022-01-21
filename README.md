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
`.map` is a array method used to run through an existing array and return it modified as a new array. MDN uses the example of multiplying all items in an array by a given figure, but it can be used to modify any detail of each of the elements in the array.
`.reduce` is used to run through the array and reducing it to a single integer. we've only used it to reduce numbered arrays to single integers so far.
`.filter` is used to parse ferret out elements with specific characteristics. It will return the desired items/array as a new constant, and reject those that don't fit the requirements.

2. Explain the difference between a callback and a higher order function.

A higher order function receives a callback function. The callback function is used as an argument for the higher order function. It serves the higher order function.

3. Explain what a closure is.

Closure pertains to nested functions. When a nested(inner) function reaches out into the outer function housing it for information needed to complete its (inner) function.

4. Describe the four principles of the 'this' keyword.

-GLOBAL- 'this' is not attached to anything in particular. In this case the console will give you the whole window and all the javascript contained therein--which is way too much information to be useful. 'This' in the global scope is an error.

-IMPLICIT- 'This' is initially written within a function as a mere place holder and lacks concrete value, UNTIL a method is called. When a method is called there is a dot in the method that correlates to the dot in 'this._____' in the original function. Whatever the method is asking you to do, to the left of the dot becomes the implicit owner of 'this', ...thus giving you guidance for how to apply the method to what function and how.
-NEW- the 'this' is reassigned by using the 'new' keyword so that 'this' now applies to the new object desired. It requires you to invoke the function and assign 'this' to the object using the 'new' keyword.
-EXPLICIT- methods such as '.call', '.apply', or '.bind' force 'this' to apply to the object explicitly named in that command

5. Why do we need super() in an extended class?

Super serves the same purpose as .call in function prototypes. Super facilitates the inheritance of all the parent class keys, values, and methods to the child class. (Super is written in the child class, calling up to the parent for that inheritance.)

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


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
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://notion.so.bloomtech.BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
