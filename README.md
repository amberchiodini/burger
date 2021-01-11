# burger

## Table of Contents: 
* Description 
* First Look 
* Technologies Used
* Installation 
* Links 
* License 
* References 

## Description 
I created a burger logger app with MySQL, Node, Express, Handlebars, and ORM that allows the user to input the names of burgers that they want to eat, to view their history of logs, and to store every burger into database whether it has been eaten or not.

## First Look: 
![burger_app](https://user-images.githubusercontent.com/69092983/104144119-a2166880-5387-11eb-9f11-9761cd6b5159.gif)

## Technologies Used:
* [NodeJS](https://nodejs.org/en/)
* [Express](https://expressjs.com/)
* [mySQL](https://www.mysql.com/)
* [Handlebars](https://handlebarsjs.com/)

## Installation:
You will first need to set-up your app by making a package.json file but running ```npm init``` into your terminal. Then you will install Express, Handlebars, and MySQL by running ```npm i mysql, express-handlebars, express``` into your terminal. From there, you will create the below recommended files and folders: 

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

## License: 
MIT License

Copyright (c) [2020] [Amber Chiodini]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## References: 
* [Stack Overflow](https://stackoverflow.com/) 
* [Heroku](https://devcenter.heroku.com/categories/reference)