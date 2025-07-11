# Tailwind-React-Setup-Configuration

### Tailwind version: 3
##### Copy and paste the following commands into your react base directory
```
npm install -D tailwindcss@3 postcss autoprefixer
```
```
npx tailwindcss init -p
```
#### In the newly created tailwind.config.js copy and paste the version that suits your specific tailwind.config.js file content
```
// tailwind.config.js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
#### Postcss.config.js is automatically generated no need to modify it
#### In index.css or your base css file override its content with the following
```
/* src/index.css */
@tailwind base;
@tailwind components;
@tailwind utilities;
```
#### Import your index.css in your app.jsx or main.jsx file
```
import './index.css'; // Import your main CSS file
```

