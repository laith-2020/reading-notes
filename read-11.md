# Welcome READ 11
EJS 

![](https://scotch-res.cloudinary.com/image/upload/w_1050,q_auto:good,f_auto/media/https://scotch.io/wp-content/uploads/2014/07/nodejs-templating-with-ejs.jpg)

When creating quick on-the-fly Node applications, an easy and fast way to template our application is sometimes necessary. So far we've been building out full MEAN applications and Angular acts as our templating engine.

For applications that need quick templating, there are many options that we can use. Jade comes as the view engine for Express by default but that syntax just flat out scares me. EJS is one alternative does that job well and is very easy to set up. Let's take a look at how we can create a simple application and use EJS to include repeatable parts of our site (partials) and pass data to our views.

## Our Test Application


We will be making two pages for our application with one page with full width and the other with a sidebar.
File Structure
Here are the files we'll need for our application. We'll do our templating inside of the views folder and the rest is pretty standard Node practices.

```
- views
----- partials
---------- footer.ejs
---------- head.ejs
---------- header.ejs
----- pages
---------- index.ejs
---------- about.ejs
- package.json
- server.js

```

### package.json will hold our Node application information and the dependencies we need (express and EJS). server.js will hold our Express server setup, configuration. We'll define our routes to our pages here.Node Setup Let's go into our package.json file and set up our project there. 

```

{
    "name": "node-ejs",
    "main": "server.js",
    "dependencies": {
        "ejs": "^1.0.0",
        "express": "^4.6.1"
    }
}
```

 EJS Partials footer.ejs, head.ejs, header.ejs
Like a lot of the applications we build, there will be a lot of code that is reused. We'll call those partials and define three files we'll use across all of our site: head.ejs, header.ejs, and footer.ejs. Let's make those files now. 
