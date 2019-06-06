# Module 2 Prep Work


## Solidifying & Building on Mod 1 Concepts

Make a fresh copy of [this google doc](https://docs.google.com/document/d/1l08-d5Vdx4r4iGCaZ3mpUm4n3SJVaPI9lqVpp5W_epU/edit#) that you can edit.  This document contains some reading material and practice exercises that will help you solidify important concepts from Mod 1. Some information might be new to you, some might be review.

You should read through this document and fill out any practice exercises or question prompts in the copy that you've created. **Send your completed copy to instructors via Slack before Day 1 of the inning.**



## jQuery 

 jQuery is a JavaScript library that makes selecting and interacting with DOM elements easier by providing a shorter, more readable syntax for doing so. When we say that something is a “JavaScript library” we mean that it’s a pre-written collection of code that makes certain tasks easier for JavaScript developers. For example, when you wanted to select an element and change its inner text in plain old JavaScript, you would have to do something like so:  

 ```js  
let mooElement = document.getElementById(‘moo-cow’);  
mooElement.innerText = ‘MOOOOO’;  
``` 

 With jQuery, we can accomplish the same thing with much less code: 

 ```js  
$(‘#moo-cow’).text(‘MOOOOO’); 
``` 

 You’ll be allowed (and encouraged) to use jQuery in your upcoming projects, so we would recommend familiarizing yourself with the library by doing the following reading and exercises:  

 * Using jQuery Core: https://learn.jquery.com/using-jquery-core/ 
    * document.ready()  
    * Selecting Elements  
    * Working with Selections 
    * Manipulating Elements 
    * Traversing  
* CodeAcademy jQuery Course: https://www.codecademy.com/learn/learn-jquery  
    * Introduction  
    * Effects 
    * Events  
    * Traversing the DOM  
* Take a Mod 1 project and incorporate the jQuery library. Refactor your DOM selections and interactions from plain JavaScript to jQuery. 


------------------------------------------------------



## Babel & Evolution of JavaScript

As the web becomes more advanced, the JavaScript language evolves and gains more features to support more complex browser capabilities. This is how we get newer versions of the language. In the current developer ecosystem, you'll hear people talking about ES5, ES6 and ES7 (E is for [ECMAScript](https://stackoverflow.com/questions/912479/what-is-the-difference-between-javascript-and-ecmascript).

In Mod 1, you mostly learned JavaScript syntax that was introduced with the ES5 version. This version is widely supported by modern browsers, and includes things like your standard `var` and `function` declarations. Browser developers are still working on supporting newer versions like ES6 and ES7.

You may have come across some ES6 syntax throughout your independent study (including variable declarations like `let`, `const`, arrow functions, and even Classes). In Mod 2, we'll expect you to begin using ES6 features and syntax where appropriate. Read more about the following ES6 features from [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read):

- From [Chapter 1: Block Bindings](https://leanpub.com/understandinges6/read#leanpub-auto-block-bindings), read:
  * the entire chapter
- From [Chapter 2: Strings](https://leanpub.com/understandinges6/read#leanpub-auto-template-literals), read:
  * Template Literals
- From [Chapter 3: Functions](https://leanpub.com/understandinges6/read#leanpub-auto-functions), read:
  * Functions with Default Parameter Values
  * The Spread Operator
  * Arrow Functions
- From [Chapter 4: Expanded Object Functionality](https://leanpub.com/understandinges6/read#leanpub-auto-expanded-object-functionality), read:
  * Object Literal Syntax Extensions
  * New Methods
  * Duplicate Object Literal Properties
- From [Chapter 5: Destructuring for Easier Data Access](https://leanpub.com/understandinges6/read#leanpub-auto-destructuring-for-easier-data-access), read:
  * Why is Destructuring Useful?
  * Object Destructuring
  * Array Destructuring'
- From [Chapter 10: Improved Array Capabilities](https://leanpub.com/understandinges6/read#leanpub-auto-improved-array-capabilities), read:
  * Creating Arrays
  * New Methods on All Arrays


When talking about different versions of JavaScript, you'll also hear about a tool called [Babel](https://babeljs.io/). Babel allows developers to use the latest and greatest JavaScript syntax, without having to worry about whether or not browsers support it yet. This works by taking any fancy ES6/ES7 code that you've written, and transpiling it down back to an older, more supported version before it reaches the browser. This transpilation process is pretty invisible to the developer, and allows you to keep yourself up-to-date with the latest language features without having to worry about your apps being broken in the browser.

Walk through this [ES6 Tutorial](http://ccoenraets.github.io/es6-tutorial/), which has you install Babel and should give some insight into what it's doing:
  - `Setting Up Babel`
  - `Using let Variables`
  - `Using Destructuring`
  - `Using Arrow Functions`


------------------------------------------------------



## JSON & Application Data

In Mod 2 you'll be working with a lot of **application data**. Familiarize yourself with:

-*What JSON is, why it exists, and where you might see it being used*  
-*The difference between JSON and a regular JavaScript object*
  - Read the [MDN Documentation](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON
) on JSON. Complete the tutorial/exercise `Active learning: Working through a JSON example`.
  - Read [this](https://www.digitalocean.com/community/tutorials/an-introduction-to-json) intro to JSON
  - Install the Chrome Extension `JSONView` to make JSON more readable in the browser 
  - Create your own JSON dataset (referencing the above resources as needed) and post it in your Slack channel for feedback

------------------------------------------------------

<!-- 


## NPM

At the start of Turing, we had you do some computer setup that involved installing and downloading a slew of tools. This trend will continue! You'll mostly be doing installations of "packages" through NPM. Familiarize yourself with:

* *what a package is, and what a package manager is*
* *what information goes into a package.json file and why it's needed*
* *the `npm init` and `npm install` commands*
* *the difference between dependencies and devDependencies*

Do some independent research on the above bullet points, then answer the following questions to the best of your ability and DM them to your instructors over the break. Your answers don't have to be formal or polished, we just want to see where your understanding is at after doing some initial research. It's ok if you feel fuzzy on the concepts, we will discuss them as a class Day 1. 

* **Why do package managers exist for front-end developers building web apps?**
* **What is npm and what does it allow developers to do?**
* **Describe what a 'dependency' is, and the difference between a devDependency and a regular dependency. Give an example of each.**



------------------------------------------------------ -->



## Linting

In Mod 1, you were given general [style guides](https://github.com/turingschool-examples/javascript/tree/master/es5) for how you should be writing your code. In Mod 2, we're going to enforce a linter. A linter helps make sure that the way you write your JavaScript conforms to certain stylistic patterns and best practices.

We'll be working with a tool called [eslint](https://eslint.org/), and your projects will be required to abide by the following [rules](https://github.com/turingschool-examples/javascript/blob/master/linters/module-2/non-react/.eslintrc). Read through the "rules" object in the `.eslintrc` file and look through the eslint documentation to [find each rule](https://eslint.org/docs/rules/), and familiarize yourself with what it does.

Set yourself up with eslint by installing it with npm. In your terminal (from any directory), run the following command:

`npm install -g eslint`




------------------------------------------------------



## Debugging

While you may have seen and used the browser's Developer Tools in module 1, we'd like you to step through this Udemy course on [Dev Tools](https://www.udemy.com/devtools-2017-the-basics-of-chrome-developer-tools/). Some of it may be review, but you may pick up some new tricks along the way!



------------------------------------------------------




## Coding: Refactor Mod 1 Projects

  - Familiarize yourself with the syntax of switch statements - *rewrite long, nested if/else statements into [switch statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch) if possible*
  - *DRY up your code*
    - Find areas where code is duplicated and break it out into a function
  - *Change for loops into `forEach`*
    - You'll be working with a lot of Array iterator methods in Mod 2 like [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach), start practicing them now!
    - Focus on: `forEach`, `map`, `filter`, `find`, `sort`, and `reduce`
  - *Try out converting some ES5 syntax to ES6*
    - You can refactor and your projects they should still work in Google Chrome
  - *Install the linter configuration and lint your JavaScript style*
    - Add the `.eslintrc` file linked above to your project directory (it must be named `.eslintrc`)
    - From your terminal, within your project directory, run: `eslint ./index.js` (or the path to whatever JavaScript file you want to lint)
    - Read through the output and fix the errors - you are given line numbers and an explanation of what's wrong for each error.


## CodeWars

If you haven't already, sign up for an account at [Codewars](https://www.codewars.com). You'll want to make doing these exercises a regular part of your practice _outside_ of the work that you are doing on projects. It is recommended that you start by filtering the exercises (Katas) so that you are coding at a Level 8. As you progress you should move into Levels 6 & 7. By the end of the module, the expectation is that you can work through what is considered the equivalent of a level 7 exercise. Doing these exercises will you give you the additional reps that are necessary to take the content that is learned in class and apply it in a different context - thus, solidifying your learning.

Please DM your CodeWars handle to all 3 instructors before intermission begins.
