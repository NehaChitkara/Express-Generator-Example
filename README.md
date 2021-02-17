# Express JS boilerplate using Express Generator

Use express-generator to create the boilerplate code 

##  Steps

Following are the steps to generate the app:

Step 1: Create a new directory and go to the directory
> mkdir newdir
> cd newdir

Step 2: Install express using npm. If you do not have npm installed, follow the steps given - 
[Install npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
> npm install express

Step 3: Install Express Generator npm module. 
> npm install express-generator@latest

Step 4: Create the directory structure by running the command "express". You can set the view engine of your choice. Available choices are: dust|ejs|hbs|hjs|jade|pug|twig|vash. you can also set css engine according to your choice by using command --css=(less|stylus|compass|sass) (defaults to plain css)
> express --view=ejs
 
Step 5: Install the dependencies
> npm install

Step 6: Start the app. 
> npm start

Step 7: Access the app using "localhost:3000". You can change the port in the file bin/www
> localhost:3000

Happy coding!

