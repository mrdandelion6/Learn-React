# React + Vite

## Setup
- Have Node.js from Node's website
- Don't need React.js installed from npm when using vite
- run: `npm create vite@latest` then name your project and choose react framework and variant (typescript or javascript).
- cd into the created react directory and run: `npm install` then `npm run dev` to start app

## Intro
React is a JS library, NOT a framework, used to easily build and arrange UI for react apps.


### Components
React uses **components** to build the frontend. A component is a self contained section of code that functions as a reusable building block.

### XML
React uses a syntax extension of JS or TS known as JSX or TSX respectively. This allows us to write HTML like code in our JS files. 

### Virtual DOM
React uses a virtual DOm which is a lightweight version of the real DOM of a web page. We can keep track of changes made the virtual DOM and apply only those specifc changes to the real DOM without needing to refresh the entire webpage.

This reduces "rendering performance overhead."

## Files in React
### node_modules
Contains external packages our build relies on. Add to .gitignore!

### public
Contains public assets such as fonts, images, and videos. They are not bundled during final output and typically available through a URL.

### src
Where the magic happens. Read below.

### src/assets
Similiar to the public folder, except files in the assets folder are bundled during final output.

### src/main.jsx
Our main JS file. Remember, React uses componenets. We add a single App componenet in this file which we import.

### src/App.jsx
You can think of the App componenet as the root component. This is where most of the front end code will go.