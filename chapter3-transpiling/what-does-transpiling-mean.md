# What does it mean to transpile your code?

Transpiling means “translating” code that’s written in one language (or a version of it) to the equivalent code written in another language (or a different version).
For example, code that’s written in ES6, JSX or in TypeScript can be transpiled to ES5, which is understood and supported by all browsers.

![transpiling](https://github.com/andreeamaco/js-boilerplate-tutorial/blob/main/chapter3-transpiling/Transpiling%20your%20code.jpg)

In this tutorial, we’ll use Babel as transpiler or source-to-source compiler.

## Why do you need a transpiler?

A logical question at this step is why use a transpiler if you’re writing your own code and if it’s all written in JavaScript? Why complicate things?

Although technically you’re correct and all the code is written in JavaScript, not everyone uses the same JS version and syntax. 

Here’s an example: a function written in ES5 syntax, followed by an ES6 arrow function.

![example-transpiling](https://github.com/andreeamaco/js-boilerplate-tutorial/blob/main/chapter3-transpiling/Transpiling%20your%20code%20(1).jpg)

As a professional developer, you’ll rarely start a project from scratch. In most cases you’ll join an existing project and you’ll work in a mixed team. 

Some of your colleagues might be using older syntax or features that aren’t yet supported by all browsers. To make sure your code doesn’t break when it’s pushed to production and to keep it consistent, you’ll use a transpiler.

Adding a transpiler to your project offers a couple of advantages:

- It helps browsers understand your code, regardless of the syntax you use
- It allows you to use your preferred language and syntax so that you can work more efficiently
- It gives your team freedom to use the syntax they’re comfortable with

Now let’s go ahead and install Babel!




