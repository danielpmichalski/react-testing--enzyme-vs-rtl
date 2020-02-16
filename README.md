# React Testing with Enzyme and React Testing Library

This codebase is a part of workshops on testing React apps using different test libraries. Currently, it focuses on the below libraries:
- [Enzyme](https://github.com/airbnb/enzyme)
- [React Testing Library](https://github.com/testing-library/react-testing-library)

## Installation

1. clone Git repository
2. install `npm` or `yarn`
3. in the cloned repository's directory run: `npm install`

## Running
### App
1. run in terminal: `npm start`
### Tests
1. run in terminal: `npm test`

## Overview
This is a React app with not a lot of styling, but a lot of functionality utilising many React features. 

It consists of components of increasing complexity. It has functional and class-based components. Some components use React Hooks, some use React Context, others use Redux store and some use Formik/Yup form handling libraries.

Many components interact with each other through either React Context or Redux store. There are some components that use mocked asynchronous data fetching calls.

All those components have been covered with unit and integration tests written with all libraries, so that a comparison of syntax, complexity, as well as performance of those test libraries, could be made.
