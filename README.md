# create tailwind version2

# step 1
npm init -y (package.json)

# step 2 
npm install tailwindcss@2.2.19 (package-lock.json & node_modules)

# step 3 
create src folder & styles.css input following code

@tailwind base;
@tailwind components;
@tailwind utilities;

# step 4 

"scripts": {
    "build-css": "tailwindcss build src/styles.css -o src/styles-live.css"
  },

# step 5 

npx tailwindcss init --full (tailwind.config.js)

Under Colors, add 
teal:colors.teal,
orange:colors.orange,

# step 6 

npm run build-css

# step 7 

under src folder 

valet link
valet links, if SSL not secure then run  valet secure

create html file and add <link rel="stylesheet" href="styles-live.css">

input https://src.test/ filename  at browser









