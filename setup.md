## How to setup Tailwind CSS 

- Tailwind Development

- Install Tailwind CSS using CLI
-------

Step 1: Run the command in terminal 
```
npm init -y
```
 => It will give package.json

Step 2:Run the command in terminal
```
 npm install -D tailwindcss
 ```
 => -D indicates that it install for dev-dependencies for development purpose

Step 3: Run the command in terminal
```
 npx tailwindcss init
 ```
 => it will create tailwind.config.js this is for custimizing the css
 and if we do=> npx tailwindcss init -y , then it will install post css file .


Step 5 : Update tailwind.config.js files instead of this
```
content: [],
```
we update like this it means in folder src if there are html and js file then tailwind will implement.
```
content: ["./src/**/*.{html,js}"],
```
 we can use this   
 ```
 content: ["*.{html,js}"],
 ```
  this means we want to include all the html and js file.and for single file like html only we can use  this.
  ```
content: ["*.html"],
```

Step 6: Create a file src/input.css and past this 
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
Step 7: Run the command 
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
Step 8: In index.html file add this code into head tag
```
<link href="src/output.css" rel="stylesheet">
```

Now you are ready to use tailwind css...



