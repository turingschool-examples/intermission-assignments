# Module 4 Intermission Assignments

## Required Work

To prepare for Module 4 we'd like for you to complete the following before 9 AM Monday (the first day of M4).

## 1. Reflection on Learning Experiences

Complete this [exercise](https://gist.github.com/neight-allen/78d1b788357d6da5a0c93c7080def654) to reflect on your learning experience thus far here at Turing.

## 2. JavaScript Fundamentals

Read the following lessons to gain a deeper understanding of JavaScript syntax and how JavaScript works. Depending on your level of knowledge with JavaScript, some of this may be a review and some of this may be new. Even if you feel confident with the fundamentals of JavaScript, we encourage you to read through the content as a refresher. This content is taken from the Front End program - we think it's a great overview of the JS basics.

* [Data Types, Variables, Conditionals, Function Basics](http://frontend.turing.io/lessons/module-1/js-1.html)
* [Function Fundamentals, Variable Scope, Loops, Arrays](http://frontend.turing.io/lessons/module-1/js-2.html)
* [Objects, This, Data Structures](http://frontend.turing.io/lessons/module-1/js-4.html)
* [Array Prototype Methods](http://frontend.turing.io/lessons/array-prototype-methods-intro)

## 3. JavaScript without a browser

We'll start with some backend JavaScript. Work through [this lesson](http://backend.turing.io/module4/lessons/javascript_without_a_browser). It will introduce you to Node.js, and basic unit testing using Mocha.

## 4. Debugging JavaScript

You've all had some experience with JavaScript thus far, but probably haven't done too much in the Node environment. Check out this [lesson](http://backend.turing.io/module4/lessons/debugging-in-node) for some basic debugging tools in Node

## 5. Sorting Suite

Complete Sorting Suite in Javascript [here](http://frontend.turing.io/projects/sorting-suite.html). Choose two out of the three fundamental sorting algorithms to complete. Use Node.js to run your code, and Mocha/Chai to write your tests. FE2 gets this as a project, so we'll use their project requirements, but you can gnore the rubric. You won't be graded. We just want you to get some practice testing and writing JavaScript.

If we're way off base with how long this will take, cut off your intermission week work at ~12 hours. When you're finished, add your repo to your forked gist from the reflection exercise in part one above.

## 6. Submit your work.

Find your document located [here](https://github.com/turingschool/ruby-submissions/blob/master/1701-b/4module/intermission_work.md), update the "Sorting Suite" and "Reflection" link next to your name, and create a PR titled `YourName-Intermission Work`. The deadline for submissions is Monday, Week 1 at 9 AM. If you anticipate that you won't meet this deadline for any cirucumstances, you need to DM your instructors. 

### Tips for JS success

Some biggies if you're coming from Ruby:

-   Methods are called Functions
-   `nil` is called `undefined`
-   `require`ing a file you've written does nothing if you didn't export from that file
-   All `return`s are explicit in Javascript. If you don't use the word `return`, your return value will be `undefined`

Google is your friend. It's totally reasonable to type things like ".each in javascript" or "what is const in javascript"

## Optional Work

All of these things were at one time part of the intermission week work. We've retooled the module, and are focused on getting you coding during intermission week. However, there's some good resources below if you want to pick and choose the things that seem interesting to you.

### Introduction to JavaScript Topics Reading

**Read** the following selections from [Speaking JavaScript](http://speakingjs.com/es5/) & [Eloquent JavaScript](http://eloquentjavascript.net//):

* [Chapter 3 (Speaking): The Nature of JavaScript](http://speakingjs.com/es5/ch03.html)
* [Chapter 3 (Eloquent): Functions](http://eloquentjavascript.net//03_functions.html)
* [Chapter 5 (Eloquent): Higher Order Functions](http://eloquentjavascript.net//05_higher_order.html)
* [Chapter 6: (Eloquent) The Secret Life of Objects](http://eloquentjavascript.net//06_object.html)
* [Chapter 17: Objects and Inheritance (Speaking JavaScript)](http://speakingjs.com/es5/ch17.html)

Then finish it all with [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/).

### Exercisms

* Complete *5* of your own completed [exercism.io][exer] exercises in JavaScript
* Review solutions by 5 other people for the same exercises, and compare your solution to theirs

If you have trouble with the exercism UI, you can find other versions of exercisms you submitted at this link:http://exercism.io/tracks/javascript/exercises

[exer]: http://exercism.io/


## Extensions

Then select and complete *one* of the sections below.

### NodeSchool.io

Work through _at least two_ of the following courses:

* [javascripting](https://github.com/sethvincent/javascripting)
* [lololodash](https://github.com/mdunisch/lololodash)
* [ExpressWorks](https://github.com/azat-co/expressworks)

### jQuery Fundamentals

Work through Bocoup's [jQuery Fundamentals](http://jqfundamentals.com).

### CSS Fundamentals

* Work Through This [Introductory Static Site](https://github.com/turingschool-examples/introductory-static-site)
* Work Through These [CSS Layout Challenges](https://github.com/turingschool-examples/css-layout-challenges)

### Scaling Up as a Developer

As we move into the final module of Turing, we're getting fairly competent at producing useful software. But rather than being the end of the journey, this really just opens the door to even deeper rabbit holes—now that I can get something done, what other ways might there be to accomplish the same thing? The same observable effects could be accomplished via numerous different combinations of code. What are the underlying opinions and ideas embodied by each choice?

**Read**: [Sandi Metz' Rules For Developers][sandi] (10 minutes)
* Which of Sandi's rules do you feel like might be the hardest to follow—why?

**Listen**: [Shop Talk: Tom Dale](http://shoptalkshow.com/episodes/147-tom-dale/) (1.5 hours)
* Do you agree with Tom? What parts of his argument are compelling? What parts do you disagree with?

Here are are a few more "philosophical" materials to hopefully help us contemplate this side of the issue:

* [Execution in the Kingdom of Nouns by Steve Yegge](http://steve-yegge.blogspot.ca/2006/03/execution-in-kingdom-of-nouns.html) - You've been doing object-oriented programming for almost 6 months now. What are some of the limitations imposed by this approach? How do Ruby and/or Javascript capture the benefits of OO while avoiding some of the pitfalls?
* [Simplicity Matters by Rich Hickey](https://www.youtube.com/watch?v=rI8tNMsozo0) - As we move into working on larger and more sophisticated systems, some of the approaches that have worked on smaller projects may no longer be so effective. What does Rich Hickey say about the common pitfalls of Ruby and Rails applications?
* [The Birth and Death of Javascript by Gary Bernhardt](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript) - This talk takes a tongue-in-cheek tone, but the concepts discussed are very topical. What does Bernhardt suggest about the role of Javascript in shaping the modern web?
* [Real Software Engineering by Glenn Vanderburg](https://www.youtube.com/watch?v=NP9AIUT9nos) - What does Glenn have to say about Software Engineering as a discipline? How does Software Engineering differ fundamentally from other Engineering disciplines? What can we as Software Engineers take away from other disciplines?

[sandi]: http://robots.thoughtbot.com/sandi-metz-rules-for-developers
[tbruby]: https://github.com/thoughtbot/guides/tree/master/style/ruby
[airbnbjs]: https://github.com/airbnb/javascript
[hound]: http://robots.thoughtbot.com/introducing-hound
[tomdale]: http://shoptalkshow.com/episodes/147-tom-dale/
[speakingjs]: http://speakingjs.com/es5/
[allonge]: https://leanpub.com/javascript-allonge/read
