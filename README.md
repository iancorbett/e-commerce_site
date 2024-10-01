# E-Commerce_Site


Intro: In this project, I was given the starter code to create an e-commerce application. I had to complete the code to make the project fully functional. Firstly, I installed all of the necessary node packages to finish the project. Then I created the four different models, Category, Product, Tag, and ProductTag. I then created all of the necessary associations between the four models, as well as all of the API routes, in order to perform the CRUD operations. After entering the data into the database, insomnia can be used to test the application.

Project description: In this project, we use pg, sequelize, express.js, and dotenv, to help us run an e-commerce application. A database is created by the user, that will ultimately hold all of the data. There are four models created, with all of their requirements listed. Associations are created between the models. This is where we define which models belong to other models. API routes have been written in order to perform various operations (post, put, get, delete). The user will run the command to seed the data in the database. The code has been written to sync the models to the database, so the user needs only to run npm start, or node server, in order to run the application. Then, insomnia can be used to double check that all of the routes are correct and work correctly. There are fifteen total routes, five for products, five for tags, and five for categories. The walkthrough video will show users how to check these routes using insomnia.

User instructions: Because this is not a deployed project users will have to run this application locally on their own computer. After cloning all of the code, first start by downloading all of the necessary node packages. this includes pg, dotenv, express, and sequelize. Then you will create a database. You will do this by opening up your integrated terminal and logging into Postgres. You will then run the schema command to create the database. Then run the command to quit out of Postgres. You will then run the command NPM run seed in order to seed all of the data to the database. The data has already been provided so you will not need to create any new data. You Will then run the command NPM run start. Now that the database has been seeded with all the correct data, and you can now open up the insomnia application. You will then test the 15 different routes as is shown in the walk-through video. The video will also demonstrate how to add or change any data that you would like!

How to contribute: In order to contribute to this project, you will need to obtain permission from the owner of the repository!

Link to the Walkthrough Video:

Sources: for this project I received help from a tutor named Joem. I had the vast majority of the code written correctly, but there were a few small issues that I was having trouble resolving, and he was able to help me fix them and get the application running correctly. For example, I did not realize that I had to rename my ENV file. In the starter code it said ".env.example", but this was supposed to be changed to .env, but I had not changed it. Therefore, it was returning an error. Additionally, he helped me fix two errors (one error made twice), in the index.JS file in the models folder. I was not using the through keyword 19 and 25 instead I passed in the model, as opposed to using the keyword “through”. Additionally, he helped me fix two small errors. These errors occurred because I forgot to include “req.params.id” on line 23 of category-routes.js, and I forgot “req.body” on line 47 of tag-routes.js. Additionally, he was very helpful in explaining how to use the application on insomnia. Otherwise no other sources were used besides obviously the source code that I was given to start the project.

License:

MIT License

License Explanation:

Copyright (c) 2024 iancorbettPermission is hereby granted, free of charge, to any person obtaining a copyof this software and associated documentation files (the "Software"), to dealin the Software without restriction, including without limitation the rightsto use, copy, modify, merge, publish, distribute, sublicense, and/or sellcopies of the Software, and to permit persons to whom the Software isfurnished to do so, subject to the following conditions:The above copyright notice and this permission notice shall be included in allcopies or substantial portions of the Software.THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS ORIMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THEAUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHERLIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THESOFTWARE.

Contact:

My GitHub username is iancorbett. Here is a link to my Github: github.com/iancorbett E-mail: iancorbett1324@gmail.com
