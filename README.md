# React Native TypeError: Cannot read properties of undefined (reading 'property')

This repository demonstrates a common error in React Native applications: `TypeError: Cannot read properties of undefined (reading 'property')`. This occurs when attempting to access a property of an object that is currently null or undefined. This frequently happens when dealing with asynchronous data fetching or component lifecycles.

The `bug.js` file showcases the problematic code. The `bugSolution.js` file provides a solution using optional chaining and nullish coalescing.

## Setup

Clone this repository and run `npm install` or `yarn install` to install the necessary dependencies.

## Running the Example

Run the app using your preferred React Native method (e.g., `npx react-native run-android` or `npx react-native run-ios`).