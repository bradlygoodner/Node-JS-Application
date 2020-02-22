# Node JS Application
-

#Environment Setup
-Download Node.js
-Check version

#Terminal
Always start the application witha npm init, this will create a package management
https://docs.npmjs.com

##Setup `~/.npmrc`


inxex.html
- Set up express
- Running express
- Logging
- Serving up HTML
- Serving static files
- JQuery


#Debugging
npm install debug

#How to start our app
Using scripts, we will be able to make running our app easier. 

###Global vs. Local
Problems with installing globally vs locally... 

Select multiple things CMD+fn+f2 

We don't want to hard code our ports

###Nodemon config
`"nodemonConfig":{
    "restartable":"rs",
    "ignore":["node_modules/**/node_modules"],
    "delay":"2500"
  }`
  
  
  
#Templating Engines
- Building an web application
- Templating Engines
- Using Pug

###Pug
Super Simple HTML <br>
Uses indents in
We have to tell <br>

Using a templating engine, we can pull some of the logic into the engine.

####Embeds
embedding some logic into our page

embeds takes an array

passing in a list 

Very Basic Pug

`html
    head
        title MyApp
    body(class=["myApp"])
        h1(id='myId') Library
        p
            h3 Sub Header
        ul
            each val in list
                li= val `
###EJS
is just html

*Need to learn about templating engines*