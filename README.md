# Chatbot Widget testing project at Hexlet:
[![Actions Status](https://github.com/failler815/qa-auto-engineer-javascript-project-89/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/failler815/qa-auto-engineer-javascript-project-89/actions) 
[![Code Coverage](https://qlty.sh/gh/failler815/projects/qa-auto-engineer-javascript-project-89/coverage.svg)](https://qlty.sh/gh/failler815/projects/qa-auto-engineer-javascript-project-89) 
[![Maintainability](https://qlty.sh/gh/failler815/projects/qa-auto-engineer-javascript-project-89/maintainability.svg)](https://qlty.sh/gh/failler815/projects/qa-auto-engineer-javascript-project-89)
<!-- [![CI](https://github.com/failler815/qa-auto-engineer-javascript-project-89/actions/workflows/ci.yml/badge.svg?branch=main&event=push)](https://github.com/failler815/qa-auto-engineer-javascript-project-89/actions/workflows/ci.yml) -->

**Chatbot Widget** is an npm package that exports a function with chat configuration passed to it as a parameter and returns a React component that represents the UI part. Configuration determines the user's interaction with the Chatbot Widget by describing various chatbot states as the chat messages and possible transitions between them as buttons for the user to click.

Testing was conducted using React Testing Library as a testing library and Jest as a test runner. Also, jest-dom library was used to get access to the additional Jest matchers to test the state of the DOM.

Testing covers the following cases:
* How the widget renders in various states.
* Transitions between states.
* How the widget integrates into another app.
* How the widget corresponds with the passed chat configuration.
* How it handles configuration errors.

## Installation
>note: the current version of Chatbot Widget was tested using Node.js v20.11.1
* Clone this repository.
* Install required dependencies:
```
npm ci
```

## How to run tests
* Run Chatbot Widget:
```
npm run dev
```
* Run tests:
```
npm test
```