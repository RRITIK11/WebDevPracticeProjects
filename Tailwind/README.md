<h1>How to install Tailwind</h1>
<p>1. npm inti</p>
<p>2. npm i vite</p>
<br>
3. npm install -D tailwindcss postcss autoprefixer\
<br>
4. npx tailwindcss init
<br>
5. create a file postcss.config.js
<br>
6. add this to that file.
<br>
<pre>
    module.exports = {
    plugins: {
        tailwindcss: {},
        autoprefixer: {},
    }
    }
</pre>
<br>
7. Add path to tailwind.config.js
or just copy this in tailwind.config.js
<br>
<pre>
    /** @type {import('tailwindcss').Config} */
    module.exports = {
    content: ["*"],
    theme: {
        extend: {},
    },
    plugins: [],
    }
</pre>
<br>
8. In package.json -> scripts -> remove test and add "start": "vite"
<br>
9. create main.css
<br>
10. add this :
@tailwind base;
@tailwind components;
@tailwind utilities;
11.link main.css to .html 
