# Eat-Da-Burger! - MySQL, Node, Express & Handlebars

[https://burgerpls.herokuapp.com/](https://burgerpls.herokuapp.com/)

![Burger demo](/public/assets/img/burger.gif)

### Overview

- Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

- Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

- Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.

- The app stores every burger in the MySQL database, whether devoured or not.

### MVC Directory structure

This app roughly follows below structure:

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

### Technology/packages used

Bootstrap

CSS 3

Express

Handlebars

Heroku

HTML 5

Javascript/JQuery

MySQL

Node
