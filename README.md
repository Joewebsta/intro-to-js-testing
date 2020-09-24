# Intro to Unit Testing with JavaScript

This small repo is intended to accompany the [Intro to Unit Testing with JavaScript lesson for Front End Module 1](https://frontend.turing.io/lessons/module-1/intro-to-testing-javascript.html).

## Set Up

- Clone down this repository
- `cd` into the directory
- run `npm install`
- Open the project in your text editor
- run `npm test tweet-test.js` to run the tests

### Why did I run `npm install`?

**TLDR:** In Module 2, you'll learn a lot more about npm and how all these things are configured. You will **not** be required to do any set up/configuration beyond running `npm install` for any project in Module 1.

`npm` ([Node Package Manager](https://www.npmjs.com/)) helps us manage JavaScript packages that we may bring into projects. Packages are pieces of code that someone (person or company) has written to make other developers lives easier. They publish them with npm, then any developer can use them, for free! For this project, we have to bring in the packages `mocha` and `chai` in order to run our tests.

Because some libraries involve a lot of code, it wouldn't be efficient for us to download all of every package every time we run a project. Once you run `npm install`, you'll see two new-to-us items in your project directory:
- `package.json`
- `node_modules`

We can think of `package.json` as the map. Every project using a package will have this file. It gives directions about what packages, and versions, it needs to run. Once you run `npm install`, your project goes out to the internet to download the code that is associated with the packages indicated in your `package.json` file. All of that code comes through in the `node_modules` directory.
