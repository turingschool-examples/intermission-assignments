# Mod 3 Pre-Work

## Instructional Pre-Work for Mod 3

### Libraries and Frameworks

* What is a JavaScript framework? [Watch this video.](https://www.youtube.com/watch?v=sXA1zpv4DhA)
* Why would we want to use a framework? [Read this article.](https://medium.com/dailyjs/the-deepest-reason-why-modern-javascript-frameworks-exist-933b86ebc445)

There are a bunch of JavaScript frameworks out there to use. At Turing, we choose to teach **React** - it's one of the most popular frameworks out there. Actually, a lot of developers will call React a library, which it is...but it can also be described as a framework. It's a little confusing, but the lines are blurred for React. Let's just say that React is a library with some rules and conventions to follow.

Complete **one** of the tutorials below to get introduced to React:
* [Tyler McGinnis's React Tutorial: A Comprehensive Guide to learning React.js in 2018](https://ui.dev/react-hooks)
* [React tutorial from the docs](https://react.dev/learn/tutorial-tic-tac-toe)
* [Original Scrimba React Course](https://scrimba.com/learn/learnreact) - In M3 the initial focus will be on learning functional components and the utilization of hooks.
* Optional: practice building a simple app in React. Think of a mod 1 project, and build that in React! We strongly encourage you to spin up a React app with [Create React App](https://create-react-app.dev/) and play around with it!


### Testing paradigms

We are going to learn a new type of testing! In Mods 1 and 2, you learned about unit testing (testing a single function or class) and integration testing (testing multiple functions/classes working together). In Mod 3, we are going to explore "end-to-end" (sometimes called E2E) testing!

* Read [this blog post](https://www.guru99.com/end-to-end-testing.html) for a high level overview of E2E
* Watch [this video](https://youtu.be/Fw98L-kcRpc) to learn about "user stories" in agile workflows - this will help us figure out how to write our E2E tests!
* Practice writing user stories by creating some user stories for a Mod 2 or Mod 1 project

### Destructuring

Destructuring is a helpful "shortcut" in JavaScript, and it's common to see it in React Code. While you'll never be *required* to use destructuring, you should definitely be able to work with it and understand how it works.

* Walk through [this lesson](https://frontend.turing.edu/lessons/module-2/intro-to-destructuring.html)

### Workflow

Workflow is something you will deal with every day on the job. Let's continue strengthening our knowledge of workflow skills with these articles.

* Review [The Difference Between Forking and Cloning a Repository](https://github.com/orgs/community/discussions/35849)
* Review [Updating a Remote's URL](https://help.github.com/en/articles/changing-a-remotes-url)

### Tooling 

* Install [Postman](https://www.postman.com/downloads/) (be sure you download the correct version for your mac) and watch [this video](https://www.youtube.com/watch?v=MRw07FQRscI)
* Install the [React Dev Tools.](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)

You'll need to make sure you've got the Xcode Command Line Tools before the mod starts. The CLT are necessary for many of React's dependencies to work as expected. 

```bash
# to see whether you have the CLT, run:
xcode-select -v

# If you don't have the CLT, run:
xcode-select --install

```

## Deliverables 

### 1. React Review *(required)*

Create a GitHub gist to answer these questions in as much detail as possible. Imagine someone is asking these questions in an interview (these are popular interview questions).

* What is a "data model", and how does it relate to the DOM in a front-end application?
* What is a "framework?" And how does it differ from a "library?"
* Why should we consider using a framework over vanilla JS like you have been doing in mods 1 and 2?
* What is a "component" in React? Why is it useful to have components?
* What is JSX?
* What are React "props?"
* What is React "state?"
* What does "data down, actions up" mean in React?

_Note:_ As you do your research, be aware that if you come across tutorials discussing class components, they may be related to older versions of React. We used to rely on class components before hooks were introduced. We _will_ be learning hooks in Mod 3, and they are now the more modern and recommended approach.  
**By 5PM on Friday of intermission, send a link to your gist in a DM to _both_ of your instructors.**

### 2. LinkedIn Updates *(required)*

Please update your LinkedIn profiles with...  

* additional skills that you’ve learned since Mod 1
* ensure you have technical keywords in your About Me professional story
* take “student” out of your headline if it’s there 
* any other updates needed to get your LinkedIn optimized for your job search  

[Here’s a refresher on our guidelines for effective LinkedIn profiles.](https://careerdev.turing.edu/resources/branding_resources) The Career Dev team will be requesting a re-submission of your LinkedIn on Friday of Week 2, and we recommend using intermission to work on this.

## Extra Resources

Here are some additional resources:

- Take a deeper dive into JSX with the [React docs](https://react.dev/learn/javascript-in-jsx-with-curly-braces) and this [tutorial](https://flaviocopes.com/jsx/)
- Take a look at the [Cypress](https://docs.cypress.io/guides/core-concepts/introduction-to-cypress). We will be utilizing end-to-end testing in M3 to test our React applications.
- [Shop Talk with Tom Dale](http://shoptalkshow.com/episodes/147-tom-dale/) (This one is a bit older but still a good introduction for thinking about why client-side applications are important and what frameworks bring to the table.)
- [Intro to JS Modules](https://tylermcginnis.com/javascript-modules-iifes-commonjs-esmodules/) (Ever been confused about `module.exports` vs `export default`? When to use `import` vs `require(`? Read this for some clarity. This article provides a clear explanation of when to use export default import/export. Although you may find some class components in the article, we've shared it with you because it effectively explains when to use each method.)
- We will have code challenges during M3 to prepare you for your interviews. If you have time, make sure to visit [Codewars](https://www.codewars.com/) and work on challenges with a 6 or 7 ranking.
- [NPM Refresher](https://ui.dev/npm/) (We're going to be using a lot of packages, make sure you're comfortable with your package manager!)
- [100 Days of CSS challenge](https://100dayscss.com/) (Do a few days of challenges to keep your CSS skills sharp)
- Watch [this video](https://www.youtube.com/watch?v=eesqK59rhGA) on details of the request/response cycle.
- Read [Fetching data with Effects](https://react.dev/reference/react/useEffect#fetching-data-with-effects) to learn about incorporating network requests in React apps.
- Watch [this video](https://www.youtube.com/watch?v=8aGhZQkoFbQ) on the event loop.
