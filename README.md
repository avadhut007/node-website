# Dockerized the application
## Docker Build and Run Image:

1. docker build -t imagename:tag .

2. docker run -d -p 8080:3000 <imagename:tag>

Now go to url ```http://localhost:8080```

-----------------------------------------------------------------------------------------

## Document
* Clone this repo: ``` git clone https://github.com/bhanushalimahesh3/node-website.git ```
* Install dependencies using [npm](https://www.npmjs.com/) javascript package manager: ``` npm install ```
* Start node server with [nodemon](https://nodemon.io/): ``` nodemon start ```
* Tune to url: ``` http://localhost:3000 ```

All boilerplate code managed by [express generator](https://expressjs.com/en/starter/generator.html) framework adhering to DRY rule. Routes are defined in routes/index.js file, static view pages are in views folder. I have implemented partials concept to avoid code redundancy in html using EJS view engine. Css and Javascript files are stored in public folder. 


## Screenshot
<img src="public/img/screenshot.png">


