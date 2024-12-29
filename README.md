# React Native: Cannot read properties of undefined (reading '...')

This repository demonstrates a common yet subtle error in React Native: the `Cannot read properties of undefined (reading '...')` error.  This often occurs when attempting to access a property of a component or object that hasn't been fully initialized or is undefined.  The example showcases the issue and its resolution.

## Bug

The `bug.js` file illustrates the problematic code.  The key is that the component is trying to use `this.state.data` before data is loaded. 