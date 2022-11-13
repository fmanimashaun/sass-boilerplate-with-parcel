# Basic setup for Sass project using parcel

## Install

1. `npm init -y` to initialize a new project

2. `npm install sass --save-dev` to install sass

3. `npm install parcel --save-dev` to install parcel

4. Create a src folder and scss subfolder with a main.scss file inside

5. inside the src folder create a index.html file

6. link your main.scss file in the index.html file with the following code:

`<link rel="stylesheet" href="scss/main.scss">`

7. In the package.json file, add the following scripts:

```
"dev": "parcel src/index.html", 
"build": "parcel build src/index.html"
```

8. Run `npm run dev` to start the project