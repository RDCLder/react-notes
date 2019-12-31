# Introduction to React

## General

- What is React
  - React is a JavaScript library (NOT framework!!!)
  - React's purpose is to show content to users and handle user interaction

- React components are made using JavaScript functions or classes

- React uses JSX
  - Looks like HTML embedded in JS code
  - Determines content of react app like normal HTML
  
- React is split into two libraries
  - **React** - knows what a component is and how to make components work together
  - **ReactDOM** - knows how to take a component and make it show up in DOM
  
## Generating a React Project

- Quickly generate a basic react project using `create-react-app`
  - Run `npx create-react-app <project-name>`

- Key dependencies
  - **Babel** - library that transpiles JS to different versions
    - Needed due to es6+ versions of JS not being supported on all browsers
  - **Webpack** - fill in later

- Use `create-react-app` if you're a novice and `react boilerplate` if you're a pro
  - For reference, I'm definitely not a pro and `react boilerplate` confuses me
  
** Building Content with JSX

- JSX
  - Special dialect of JS
  - Browsers don't understand JSX; we use tools like Babel to convert it to es5
  - Similar to HTML with a few key differences
