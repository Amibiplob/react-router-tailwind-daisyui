# Command
```
 npx create-react-app my-project
 cd my-project
 npm install -D tailwindcss postcss autoprefixer
 npx tailwindcss init -p
 npm i daisyui
```
## React Router
```
npm install react-router-dom
```
### tailwind.config.js
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [require("daisyui")],
}
```
### index.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
### Chrome JSON Viewer
```
https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh
```
### Node JS
```
https://nodejs.org/en/download/
```
### Git Scm
```
https://git-scm.com/download/win
```
