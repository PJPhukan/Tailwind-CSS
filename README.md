# How to setup tailwind css

### Step:1-> Install Tailwind CSS:
Run the following commond :
```
npm install -D tailwindcss
npx tailwindcss init 
```       

### Step:2-> Configure your template paths :
Update your tailwind.config.js file to :
```
content: ["./src/**/*.{html,js}"],
``` 

### Step:3-> Create src/input.css file :
Include the following text :
```
@tailwind base;
@tailwind components;
@tailwind utilities;
``` 

### Step:4-> Start the Tailwind CLI build process:
Run the following commond on terminal :
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
``` 

### Step:5-> Include output.css file into the index.html file:
```
<link rel="stylesheet" href="./src/output.css">
``` 

