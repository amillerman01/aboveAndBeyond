# Above And Beyond <!-- omit in toc -->

Will be full of cool code beyond the scope of classes, as well as resources students can use to make development more fun and accessible.

This will also be a place where students can come and post questions they have about any code, and have the answers posted here!

If you want to contribute to this repository, please email me. Post any questions you have as issues on the respository itself.

- [Cool tools](#cool-tools)
  - [vscode.dev](#vscodedev)
  - [CodeSandbox.io](#codesandboxio)
  - [Stackblitz.com](#stackblitzcom)
- [Cool things in JavaScript](#cool-things-in-javascript)
  - [Operator precedence (for all 19 types!)](#operator-precedence-for-all-19-types)
  - [Methods with infinite parameter inputs](#methods-with-infinite-parameter-inputs)
- [Fun code samples](#fun-code-samples)
  - [Creating a JavaScript linked list (soft of)](#creating-a-javascript-linked-list-soft-of)
  - [Replace characters in a string](#replace-characters-in-a-string)
- [Practice algorithms](#practice-algorithms)

# Cool tools

## vscode.dev

You can access your code and make changes in visual studio code directly in the browser! Go to the repository in github, navigate to the folder that contains the code you want to view/edit, and change the start of the url from "github.com" to "vscode.dev/github". 

## CodeSandbox.io

You can run any repositories basic front end code in codesandbox by visiting the repository on github, going to the folder that contains the index.html file, and changing the start of the url from "github.com" to "githubbox.com" (make sure it's got 2 b's). This will lead you off to the codesandbox.io version of the repository. 

**Note updates you make in codesandbox don't update your code on github.**

You can do this with any branch, or any specific commit's codebase on the repository as well. If you're using custom libraries in your code, sometimes it will not load correctly in codesandbox, but I'm still trying to work out why that happens and how to fix it.

## Stackblitz.com

You can run any repositories front end application that uses angular, react, vue and many more! Go to the repository in github, navigate to the folder that contains the package.json file, and change the start of the url from "github.com" to "stackblitz.com/github". 

**Note updates you make in stackblitz don't update your code on github.**

You can do this with any branch, or any specific commit's codebase on the repository as well. Currently if you're using angular with angular material, it will not load custom themes in angular13 or higher, so just use a default theme for testing.

# Cool things in JavaScript

## Operator precedence (for all 19 types!)

There are a lot of operators in JavaScript, some of which I'm still learning about too, and you can see their order of operations here!
> https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence#table

## Methods with infinite parameter inputs

Imagine being able to process an unlimited number of paramters in a method. You can do this different ways in several languages, but here's how you can do it in JavaScipt!

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters

# Fun code samples

## Creating a JavaScript linked list (soft of)

This jsfiddle contains several ways to create a linkedList using nested objects in JavaScript, including using recursion and [multiple variable assignment](https://electrictoolbox.com/javascript-multiple-variable-assignment/) . I'll put it in its own file/folder here soon
https://jsfiddle.net/amillerman/279tr1no/2/

## Replace characters in a string

Needed this in order to build a readme file, and generate local links in the readme file to headings. Objects with characters as the keys are a fun little quirky thing you can do in JavaScript!

https://jsfiddle.net/undmbpfk/1/


# Practice algorithms

- Fibonacci
- Factorial
- Binary search
- Bubble sort
- Insert sort
- 