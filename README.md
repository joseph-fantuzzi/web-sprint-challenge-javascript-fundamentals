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

    The .map() method creates a new array and takes a callback function as an argument. The .map() method is good to use when needing to manipulate an array data set. One use case would be if we had an array of numbers and we needed to perform a task on all of the numbers in the array. For example, let's say we wanted to multiply each number in the array by 10. The .map() method would allow us to get the job done.

    The .reduce() method gives back a single value. This method takes in two arguments. A callback function is the first argument, which has two parameters: the accumulator and the current value. The second argument for the .reduce() method is the initial value. A good use case for this method would be if we had an array of numbers and we wanted the sum of all of those numbers. The .reduce() method would be able to get the job done. 

    The .filter() method creates a new array with elements that satisfy a given condition. This method takes a callback function as an argument. Whatever is written after the return statement is the conditional. If the items in an array satisfy that conditional statement, then those items get pushed to the new array. A good use case for this method would be if we have an array of objects. Each object is a person and has properties of age, name, and location. We can use the .filter() method to place all of the people objects that are 21 years or older into a new array. 

2. Explain the difference between a callback and a higher order function.

    A callback function is a function that gets passed into a higher order function as an argument. A higher order function is a function that receives a callback function as an argument.

3. Explain what a closure is.

    Closure is when a nested function within an outer function reaches to the outer function's scope to receive a variable or parameter. 

4. Describe the four principles of the 'this' keyword.

    Window Binding - 'this' will return the window object if used in global scope.
    Implicit Binding - applies to objects with methods, when the function is invoked look to the left of the dot and that is what 'this' refers to.
    Explicit Binding - .call(): will immediately invoke the function, we pass the this keyword and then the arguments 1 by 1
                        .apply(): will immediately invoke the function, we pass the this keyword and then the arguments as an array
                        .bind(): we pass in the arguments 1 by 1, it does not invoke the function, instead it returns a brand new function that can be invoked later
    New Binding - applies to constructor functions, initialized using arguments

5. Why do we need super() in an extended class?

    We need super() in an extended class because it allows us to inherit the properties of its parent class. Extends tells super what to super to. Extends and super do what Object.create and Parent.call do for prototype syntax.

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
