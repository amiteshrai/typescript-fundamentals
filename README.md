# TypeScript Fundamentals

## About TypeScript

TypeScript is a statically typed language that is superset of JavaScript. It was made public in the year of 2012. TypeScript enforces static typing to catch potential bugs/issues in the codebase during development and thus reduces the need for some unit tests.

TypeScript removes types, interfaces and aliases during transpiling and produces common JavaScript code. TypeScript doesn't override existing JavaScript behavior or try to supersede it. Preserving runtime behavior makes TypeScript compatible with all JavaScript code and ideal for experimentation.

## Philosophy Of TypeScript

1. Identify code that may produce a runtime error.
2. Provide a structure to scale a large codebase. JavaScript can be difficult to maintain when a large team is actually working and contributing to the codebase.
3. Do not impose any overhead on the produced JavaScript code and produce clean and recognisable JavaScript.
4. Make the language composable and easy to use.

## Why Use TypeScript?

1. TypeScript is fast and has excellent intellisense.
2. TypeScript brings static typing and allows you to generate ECMAScript, thus enabling cross-browser compatibility.
3. TypeScript is easier to refactor and maintain.
4. TypeScript lets you use the libraries and frameworks you already know as a developer.
5. TypeScript allows you to avoid potential pitfalls that you can only find at runtime.

## Advantages Of TypeScript's Type System

1. Helps us find errors
2. Analyzes our codes as we type
3. Only exists in development

## Installing TypeScript

Before installing TypeScript, ensure that you have `NodeJs` and `NPM` installed on your system.
After installing `NPM`, use the following command to install TypeScript globally.

    npm install -g typescript

To install TypeScript locally:

    npm install typescript --save-dev

Upon successfull installation of TypeScript, check the version of TypeScript installed on your system using the following command.

    tsc -v

To run the TypeScript compiler, use:

    npx tsc

Here, `tsc` stands for TypeScript Compiler.

## Useful Resources

1. [TypeScript QuickStart](https://www.typescriptlang.org/docs/handbook/release-notes/overview.html)
2. [TypeScript Playground](https://www.typescriptlang.org/play)
3. [ECMAScript 2015 Language Specification](https://www.ecma-international.org/wp-content/uploads/ECMA-262_6th_edition_june_2015.pdf)
