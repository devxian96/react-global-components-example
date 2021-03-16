# react-global-components Example
> This project is basic react boilerplate code.   
> This project doesn't suggest to you about nice file structure and coding style.   
> ***Only show you about react-global-components how to use it.***

## Where I am editing this source file

It is version number based on [NPM](https://www.npmjs.com/package/react-global-components)(react-global-components@0.0.19)   
```javascript
// src/index.js
/* eslint-disable react/jsx-no-undef */
/* eslint-disable no-undef */
import "./index.css";
import App from "./App";

// This is React Global Components Entry
import ReactGlobalComponents from "react-global-components";
ReactGlobalComponents();

ReactDOM.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
  document.getElementById("root")
);

// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
reportWebVitals();
```
And all imports move to plugins directory.

## How to run?
1. git clone
2. yarn
3. yarn start