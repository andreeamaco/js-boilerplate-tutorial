# # How to set up a JS dev environment

As a self-taught front end developer with no CS or IT background, I had a hard time understanding why professional developers need so much extra stuff for their work.
My project folders included three files: index.html, styles.css and scripts.js, with some extra files in case of multi-page websites.

But that was all, and I couldn’t figure out why real web devs need so many additional tools, like pre-processors, linters, module bundlers or package managers.

I knew that I was missing something, but I just couldn’t put my finger on what it was. So I decided to change my approach to learning and to go back to the big picture. From there on, it all made sense.

This tutorial is therefore meant for **self-taught developers** who want to work like real web devs and to get ready for a junior position.

## What we’ll cover:

1. What is a JavaScript development environment?
    1. Dev vs. production environments 
    2. Source code vs. production build
    3. What a boilerplate or starter kit is
2. Node and npm for package management
    1. Install Node.js and npm
    2. Understand the package.json file
3. Transpiling your code 
    1. What does it mean to transpile your code?
    2. Why do you need a transpiler?
    3. Install Babel for JS transpiling
    4. Configure Babel
4. Module bundling
    1. Install Webpack for module bundling
    2. Configure Webpack for development 
    3. Configure Webpack for production
5. Setting up a development web server 
    1. Set up a server with Express
6. Task automation 
    1. Automate tasks with npm scripts
7. Preparing your code for production
    1. Install ESLint for linting
    2. Sourcemaps 
    3. Minification
8. Automating the production build
9. Deploying your project to GitHub pages

## What’s a JS development environment?

As a beginner, whenever you start a new project, you only think of your current needs, and you always start from scratch when creating your files.

Web devs look at the big picture and analyze the current and future needs of their project before writing a single line of code. Based on that, 
they choose tools and libraries that will help them code faster and avoid repetitive, manual tasks.

Then, they build the core folder structure, install all the dependencies and configure the tools to perform the desired actions. All this preparatory work takes time, 
so in order to avoid going through the same project again and again, developers use boilerplates or starter kits.

These are _“pre-made”_ packages that include the minimum amount of files and dependencies needed for a front end project, regardless of what you’re building.

So in this tutorial we’ll go through the entire process of creating a front end starter kit (a JavaScript development environment), and I’ll explain the why 
and how of every step. At the end of the course, you should be able to set up your own JS dev environment and deploy your first project to production.

As this is a super long tutorial, I encourage you to bookmark it and keep it as reference. You can also access the boilerplate here:
https://github.com/andreeamaco/js-boilerplate
