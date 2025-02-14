# React
- Created by Facebook
- Is a client-side JavaScript Library
- Quickly renders on the page
- Companies transisitioning more to React
  - Netflix, Uber, Dropbox, AirBnB
- Works through **Components**

## Rules of JSX
1. **Must** Export for it to be used.
2. **Must** be imported to be used.
3. **Must** be mounted to be used.
4. **Must** only return **ONE** JSX Element.

# Create a React App
- `npx create-react-app react-app-name`
- **npx create-react-app [your project name]**

## Points of Interest
- public
  - `index.html`: What is displayed to the browser.
- src
  - `index.js`: JS being rendered to `index.html`.
  - `App.js`: Main point where components are mounted. This is being rendered within `index.js`.

## About Me Challenge
```js
/* 
  - Create a new folder called aboutme within the components folder.
  - Create a new file inside the folder called AboutMe.jsx.
  - Create a <p> tag that notes where you grew up. 
    - Use variables for city and state.
  - Create an unordered list with the last 3 places you have visited. (Target, Alaska, the Kitchen, etc.)
  - Export the component.
  - Import the component into App.jsx and mount it between the Header and Footer components.
*/
```