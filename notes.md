# Instructions to get this project going

check out the docs --> https://tailwindcss.com/docs/installation    

1. Create a folder 
2. Install tailwind via npm and create the tailwind.config.js file using these command line 
    `npm install -D tailwindcss`
    `npx tailwindcss init`
3. Create a src folder and create the main css file(input.css) and place the following commands 
    `@tailwind base;`
   ` @tailwind components;`
    `@tailwind utilities;`
4. Create a build folder and make a html file in it
5. Type out this command in the terminal
    `npx tailwindcss -i ./src/input.css -o ./build/css/style.css` - thw -i is to indicate the main css file while the -o is to indicate where you'll like it to be outputted (how i understand it 💀)
6. Type out this command in the terminal. 
    `npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch` - this is how you compile tailwind
7. Start writing html code and writing classes and styles to those elements. 