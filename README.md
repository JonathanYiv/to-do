# To Do Project

This project is to practice JavaScript by implementing a To Do webapp with the following requirements:
* Projects
* Projects have Tasks
* Tasks have Titles, Descriptions, Due Dates, Priority Levels
* Data is stored in LocalStorage

This is a project from [The Odin Project](https://www.theodinproject.com/courses/javascript/lessons/todo-list).

Screenshot here...

## Pre-Project Thoughts

I would like to put some more effort into this project than normal because:

A) I need to practice JavaScript. There's a lot of concepts and functions and my irregular practice has made me feel unsteady.

B) I'd like to play around with what the last lesson introduced: Object Role Stereotypes. (Which is apparently under the umbrella of responsibility-driven development now).

Some other fun things to add:
1. NPM Task Runner scripts for webpack
2. Webpack Sass Integration

### Picking JavaScript Design Patterns
I will use factory functions and the ES6 Modules along with Module Patterns if possible.

### Modeling the App

* A Controller object that reacts to on-screen events and handles delegation to DOM Manipulation objects (View), updating the LocalStroge with the Interfacer Object (Model)
* DOM Manipulation objects to add/remove tasks and projects
* An Interfacer object to interface with LocalStorage
* A Structurer object that knows which tasks are associated with which projects

### Realization

So I wrote the above and realized I am literally making an MVC. So let's just make a JS MVC with Factory Functions, ES6 Modules, and the Module Pattern.

## Post-Project Thoughts

...
