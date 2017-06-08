
“In the beginner's mind there are many possibilities, but in the expert's there are few”

## Resources:

## Background:
### Material-UI
http://www.material-ui.com/#/get-started/required-knowledge

### Netflix JavaScript Talks - React plus X: Best Practices for Reusable UI Components
https://www.youtube.com/watch?v=Yy7gFgETp0o

  Components should be:

  Self sufficient
    Not reliant on parent component or app
    Data comes from parent app
  Easy to integrate with and understand
    Good notes and documentation
  Just enough state to be useful

  As few props as possible
  No backdoors

  Why?
  JSX/ no templates, means fewer files
  UI components can be independent of data source and still have control over the interaction


### Getting Started with Redux - Dan Abramov
https://egghead.io/lessons/javascript-redux-the-single-immutable-state-tree

### Cheatsheets
https://egghead.io/react-redux-cheatsheets


### The Changelog Podcast: Redux, React, and Functional JavaScript with Dan Abramov
https://changelog.com/podcast/187

### Dan Abramov - Live React: Hot Reloading with Time Travel at react-europe 2015
https://www.youtube.com/watch?v=xsSnOQynTHs

### Redux docs
http://redux.js.org/docs/introduction/Motivation.html

### Should I use React.createClass, ES6 Classes or stateless functional components?
http://jamesknelson.com/should-i-use-react-createclass-es6-classes-or-stateless-functional-components/


## React vs Angular reading:

### Angular vs. React - the tie breaker
https://www.airpair.com/angularjs/posts/angular-vs-react-the-tie-breaker

### React vs AngularJS – How the two Compare
https://www.codementor.io/reactjs/tutorial/react-vs-angularjs

### Angular 2 vs React: The Ultimate Dance Off
https://medium.com/javascript-scene/angular-2-vs-react-the-ultimate-dance-off-60e7dfbc379c

### Angular vs React : A Side-By-Side Comparison
https://www.pluralsight.com/guides/front-end-javascript/angular-vs-react-a-side-by-side-comparison

### React vs Angular: An In-depth Comparison
https://www.sitepoint.com/react-vs-angular/

### Angular 2 versus React: There Will Be Blood
https://medium.freecodecamp.com/angular-2-versus-react-there-will-be-blood-66595faafd51

#### Ang's strengths
##### Framework vs Library
    "Since Angular is a framework, it provides significantly more opinions and functionality out of the box. With React, you typically pull a number of other libraries off the shelf to build a real app. "

##### Typescript enforces consistency, in React much ES5 and ES6 all over the place
    Sure, TypeScript isn’t loved by all, but Angular 2’s opinionated take on which flavor of JavaScript to use is a big win. React examples across the web are frustratingly inconsistent — it’s presented in ES5 and ES6 in roughly equal numbers

##### Ang more mature, maintained by one team. React relies on ecosystem of open source libs that can churn

##### Tooling - support for JSX (now not a concern i don't think)

#### React strenghts
##### JSX
      everything in one file - code completion helps coding components (not in a separate file)

##### Fails fast and explicitly
      JSX will fail at compilation, not at run-time like in Ang.
      It will also give you line number - speeds development

##### JS centric
    "Angular 2 continues to put “JS” into HTML. React puts “HTML” into JS."
    "JavaScript is far more powerful than HTML. Thus, it’s more logical to enhance JavaScript to support markup than to enhance HTML to support logic."
    "Ember: {{# each}}
    Angular 1: ng-repeat
    Angular 2: ngFor
    Knockout: data-bind=”foreach”
    React: JUST USE JS. :)"

##### "Luxurious Dev experience"
    "JSX’s code completion support, compile-time checks, and rich error messaging already create an excellent development experience that saves both typing and time"

##### Size
      It's way smaller (up to 4 times in a simple todo app (Ang 2 will get smaller)), not a complete framework with a bunch of functionality you aren't even using

##### Embraces the Unix philosophy
      "The philosophy of small, composable, single-purpose tools never goes out of style."# react-redux-resources
