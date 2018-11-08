# Module 2 Prep Work



## Babel & Evolution of JavaScript

As the web becomes more advanced, the JavaScript language evolves and gains more features to support more complex browser capabilities. This is how we get newer versions of the language. In the current developer ecosystem, you'll hear people talking about ES5, ES6 and ES7 (E is for [ECMAScript](https://stackoverflow.com/questions/912479/what-is-the-difference-between-javascript-and-ecmascript).

In Mod 1, you mostly learned JavaScript syntax that was introduced with the ES5 version. This version is widely supported by modern browsers, and includes things like your standard `var` and `function` declarations. Browser developers are still working on supporting newer versions like ES6 and ES7.

You may have come across some ES6 syntax throughout your independent study (including variable declarations like `let` and `const`, arrow functions, and even Classes). In Mod 2, we'll expect you to begin to consistently use ES6 features and syntax where appropriate. Read more about the following ES6 features from [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read):

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


When talkin about different versions of JavaScript, you'll also hear about a tool called [Babel](https://babeljs.io/). Babel allows developers to use the latest and greatest JavaScript syntax, without having to worry about whether or not browsers support it yet. This works by taking any fancy ES6/ES7 code that you've written, and transpiling it down back to an older, more supported version before it reaches the browser. This transpilation process is pretty invisible to the developer, and allows you to keep yourself up-to-date with the latest language features without having to worry about your apps being broken in the browser.

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



## NPM

At the start of Turing, we had you do some computer setup that involved installing and downloading a slew of tools. This trend will continue! You'll mostly be doing installations of "packages" through NPM. Familiarize yourself with:

* what a package is, and what a package manager is
* what information goes into a package.json file and why it's needed
* the `npm init` and `npm install` commands
* the difference between dependencies and devDependencies

*(NPM Resources to come)*



------------------------------------------------------



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

  - *rewrite long, nested if/else statements into [switch statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)*
    - familiarize yourself with the syntax of switch statements
  - *DRY up your code*
    - find areas where code is duplicated and break it out into a function
  - *change for loops into `forEach`*
    - you'll be working with a lot of Array iterator methods in Mod 2 like [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach), start practicing them now!
  - *try out converting some ES5 syntax to ES6*
    - you do not need to set up babel to do this, you can simply refactor and your projects should still work in Google Chrome
  - *install the linter configuration and lint your JavaScript style*
    - add the `.eslintrc` file linked above to your project directory (it must be named `.eslintrc`)
    - from your terminal, within your project directory, run: `eslint ./index.js` (or whatever JavaScript file you want to lint)
    - read through the output and fix the errors - you are given line numbers and an explanation of what's wrong for each error!
