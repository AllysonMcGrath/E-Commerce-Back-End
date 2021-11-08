# E-commerce Back End-MySQL, Sequelize, 

## Description

This is a project where we were given a working Express.js API and required to use Sequelize to connect to a MySQL database. This meant adding code to connect to MySQL when you run the application, adding models for Category, Product, Tag, and ProductTag, adding the associations between those tables, and then creating API routes to connect to the data. The application allows the user to get all categories/products/tags, get one category/product/tag based on id, and create, update, and delete a category/product/tag based on id. 



## Installation

To download the repository, use the following command:

$ git clone https://github.com/AllysonMcGrath/cbcchallenge11.git

Detailed instructions for cloning GitHub repositories can be found [here.](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository)

To use this application, you need to install the dependencies with the following commands:

npm install<br/>
npm install inquirer<br/>
npm install dotenv<br/>
npm install mysql2<br/>

To create the database, you must log in to MySQL and source db/schema.sql.

To seed the database, run 'npm start' from the command line.

## Usage

When testing in Insomnia Core, all routes should look like those shown in the video below:

https://watch.screencastify.com/v/CMUW7MpXwRjQBlZgshYZ


## Credits

Trilogy Education Services, LLC, a 2U, Inc. brand

[Coding Boot Camp at UT](https://github.com/the-Coding-Boot-Camp-at-UT)

[Xander Rapstine](https://github.com/Xandromus)

[John McCambridge](https://github.com/nol166)


## License

MIT License

Copyright (c) 2021 Allyson McGrath

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
