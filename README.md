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