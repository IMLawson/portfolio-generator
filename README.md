# Portfolio-Generator

## Description

This is a node.js based application that will gather user data by prompts and then contain it in a data array to be displayed on an HTML page with CSS styling. This application is used to gather user information first, such as name, gitHub username and personal information if desired. After the user information is entered, it then takes the user through a series of prompts to gather project information. The user can provide a project name, short description of the project, a gitHub link to the project that is being input and then questions whether the user would like to have this project featured or not. 

This application is really useful in gathering data from a user about their projects that they have created and showcasing them on and HTML page. The user interface in node is extremly straightforward and easy to use. After all the user information and project information is gathered it will generate and index.html file that can be opened in a web browser. The index.html file is generated in the /portfolio-generator/dist folder after the user and project information is gathered.

The objective of this application is to create an easy to read portfolio page that can show all of your accomplishments with weblinks for prospective employers. What makes it so great is that you can enter all the projects that you have worked on and completed but you don't neccesarily have to feature all of them in your portfolio. What also makes it advantageous, is the github links that will take you directly to the project repository.

Upon completing this project I had noticed that a lot of the mistakes I was making were mostly syntax errors. The node.js application made it easier to find these errors because of the asynchronous function and promise structure. I found that the error messages were easy to understand, which made fixing all my errors go that much faster. I have learned that using the asynchrous functions that use promises to be much easier to understand and in my opinion, easier to use.

## Installation

Requirements:
Node.js which can be found here:https://nodejs.org/en/
with Install instructions here:https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs

You will also need to install NPM (Node Package Manager):https://www.npmjs.com/
After you have NPM installed you will need to get Inquirer:[  ](https://www.npmjs.com/package/inquirer) This is an embeddable command-line interface for Node.js

1 - First install Node.js and NPM using the instructions in the links. After you have those installed you need to download the Inquirer command-line interface.

2 - Create a file directory on your hard drive where you can store the repository files and have the ability to run the terminal and node application.

3 - After you have created the file directory, clone the repository to the file directory (https://github.com/IMLawson/portfolio-generator.git)

4 - When the repository file directory has been cloned into the file directory you created on your hard drive, CD into the root directory of the application.

5 - Using the command terminal enter in 'node app' (This initiate the node application and begin prompting the user for data)

6 - After entering in your personal information and project information for as many projects as you would like to be featured on your portfolio it will create an index.html file.

7 - When that index.html is created it will be put into the 'dist' file directory.

8 - CD over into the 'dist' file directory and type open index.html in the command terminal. The file will open on whatever web browser you have designated as your default web browser. The application will display all the information the user has provided for each project on the stylized HTML page.

Link to tutorial:
https://courses.bootcampspot.com/courses/1381/pages/9-up-and-running?module_item_id=527476

## License

MIT License

Copyright (c) [2022] [Ian Lawson]

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
