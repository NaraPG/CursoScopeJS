# Closures and Scope in JavaScript

## This repository
In this course we'll understand the scope functions and closures in JavaScript and at the same time what implies working with this tools and the reasons of their importance. We learned how to debug and the hoisting concept.

## Introduction

#### What is the scope
> The scope is a policy that manages the availability of variables. A variable defined inside a scope is accessible only within that scope, but inaccessible outside.
> In JavaScript, scopes are created by code blocks, functions and modules.

#### What is a closure
> A closure is a feature in JavaScript where an inner function has access to the outer (enclosing) function’s variables — a scope chain.
> * The closure has three scope chains:
>    * it has access to its own scope — variables defined between its curly brackets
>    * it has access to the outer function’s variables
>    * it has access to the global variables


## Main content
> - Example of a closure
>    * Simple closure
>    ```
>    function outer() {
>     var b = 10;
>   function inner() { 
>     var a = 20; 
>     console.log(a+b);
>       }
>   return inner;
>    }
>   ```

> - `Debugger`: Debugging is the process of detecting and removing of existing and potential errors (also called as ‘bugs’) in a software code that can cause it to behave unexpectedly or crash
> - `Hoisting`: is the default behavior of moving all the declarations at the top of the scope before code execution. Basically, it gives us an advantage that no matter where functions and variables are declared, they are moved to the top of their scope regardless of whether their scope is global or local.
> - `Scope`: in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. 
> The two types of scope are `local` and `global`
>    * `Global` variables are those declared outside of a block
>    * `Local` variables are those declared inside of a block

## Dependencies
> - Install [VS Code](https://code.visualstudio.com/download)
> - Install [Node.js](https://nodejs.org/en/)
> - Install nodemon (Optional)
>   * Cloning with git or by using npm (the recommended way):
> ```
> npm install -g nodemon
> ```
>   * You can also install nodemon as a development dependency:
>   ```
>   npm install --save-dev nodemon
>   ```
>   

## Run Code
> You can only run this project by file, using the extension [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) then select the code and use left click and `Run Code` . Now you'll see the code running in the terminal.

## Technologies
> JavaScript

## Document Structure
    |--scr
    |   |--closure
        |   |--closure.js
            |--lexical.js
            |--loops.js
            |--private.js
    |   |--debug
            |--index.js
    |   |--hoisting
            |--index.js
    |   |--scope
            |--block.js
            |--function.js
            |--global.js
            |--local.js


_Created by Nara Peña Gámez._



