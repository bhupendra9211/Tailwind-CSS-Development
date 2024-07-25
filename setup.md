How to setup Tailwind CSS 

Tailwind Development

Install Tailwind CSS using CLI

Step 1 : npm init -y
 => It will give package.json

Step 2 : npm install -D tailwindcss
 => -D indicates that it install for dev dependencies for development purpose

Step 3 : npx tailwindcss init
 => it will create tailwind.config.js this is for custimizing the css
 and if we do=> npx tailwindcss init -y , then it will install post css file .

Step 4 : further we can follow this : https://tailwindcss.com/docs/installation

Step 5 : In tailwind.config.js instead of this   content: ["./src/**/*.{html,js}"], we can use   content: ["*.{html,js}"], this means we want to include all the html and js file.and for single file like html only do   content: ["*.html"], this.

Step 5 : link:css -> this will generate css link formate : type this into index.html 




