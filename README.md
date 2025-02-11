# React Native: accessing state property before it's set

This repository demonstrates a common error in React Native applications where a state variable is accessed before it has been properly initialized, leading to a `TypeError: Cannot read properties of undefined (reading 'name')` error. The solution involves conditional rendering to check if the state variable is defined before trying to access its properties.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run the application using your preferred React Native method.
4. Observe the error message in the console, indicating the problem with accessing a property of `data` before it's set.