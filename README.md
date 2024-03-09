<div float="left" align="middle"> 
 

 #  Image Processing Fullstack App 
 
 <font size= "50">(Mobile-Responsive)</font>

</div>

####

**This is my first full stack application** , An image processing application build to apply some processes on image server-side, built with   React, CSS, Node, Express & TypeScript . 

it is a one week project was created to be submitted as 1st task in my Udacity FWD Web-Development Scholarship .

Project requirements was only the node-server but I was having the time to built the front-end project and integrate them together.
<details ><summary> 
 
 ### Project Requirements 
 </summary>
 
 You will be building an API that can be used in two different ways. As a simple placeholder API, the first allows you to place images into your frontend with the size set via URL parameters (and additional stylization if you choose) for rapid prototyping. The second use case is as a library to serve properly scaled versions of your images to the front end to reduce page load size. Rather than needing to resize and upload multiple copies of the same image to be used throughout your site, the API you create will handle resizing and serving stored images for you.

You will set up your Node.js project from scratch, installing all dependencies, and write install all necessary configurations to make your dependencies work together. Even though the project being built is quite simple, the way you set up this project will be scalable enough to move to an enterprise-level solution in the future. Imagine needing to process hundreds of images with multiple thumbnail sizes for an eCommerce solution. This project provides the building blocks for that level of functionality.

In addition to setting up and creating the functionality, you will be using industry best practices to ensure that your code is as scalable as the architecture you create. Using TypeScript, Unit testing, linting, and formatting, you will write code that is not only easy to read but is maintainable, less error-prone, and easier to debug. At the enterprise level, it becomes possible that hundreds of people may need to interact with your code, so being able to work within standards is imperative to your success.
</details>
<details open ><summary> 
  
  ### Screen Shots
  </summary>
  
  Desktop | Mobile
-|-
<img src="https://github.com/3amr7ussein/Image-Processing-Fullstack/blob/main/server/assets/full/Image-Resizing-Desktop.jpg" width='700'/> | <img src="https://user-images.githubusercontent.com/34787413/207199430-3a157ae0-e7c3-46eb-a4ab-dbd49f762faa.jpg" width="200" />
</details  >

  <details ><summary>  
  
### How To Run Project
   </summary>  
  
####  Run Server (Backend)
1- Clone project into your local machine (npm & git must be globally installed).
  
2- use your terminal to `cd server` and then `npm run install` ,this will install the required packges to run this project.

3- run `npm start` or `npm run start:prod` , to run project in development or production on PORT:5000 .

###### Other Scripts
  Script | Functionality
  :-|:-
  `npm run test`  |  to build the project and start unit testing with jasmine
  `npm run format` |  to format code.
 `npm run lint`   |  to Find problems in code

####  Lets Run Client-Side (Frontend)
  Hint : Keep the server running and open new terminal

  1- `cd client` and then `npm run install` ,to install the required packges to run client code.

  2- run `npm start` , and visit to http://localhost:3000

 </details>

  <details><summary> 
  
### API Endpoints

  </summary>
    
  
| HTTP Verbs | Endpoints             | Action                                                                         |
| ---------- | --------------------- | ------------------------------------------------------------------------------ |
| GET        | /api/images/all       | To retrive list of file in Full directory as an Array                          |
| GET        | /api/images/:filename | To retrive single image by file name                                           |
| GET        | /api/images?          | To retrive a resized image by passing query parameters (filename,width,height) |
| POST       | /api/upload           | To upload jpg image to /full directory                                         |
  
  
</details>


  
  <details><summary> 
  
###  Technologies Used
</summary>

  - [NodeJS](https://nodejs.org/) This is a cross-platform runtime environment built on Chrome's V8 JavaScript engine used in running JavaScript codes on the server. It allows for installation and managing of dependencies and communication with databases.

  - [ExpressJS](https://www.expresjs.org/) This is a NodeJS web application framework.

  - [ReactJs](https://reactjs.org/) A JavaScript library for building user interfaces

  - [axios](https://axios-http.com/docs/intro/) Axios is a promise-based HTTP Client for node.js and the browser. It is isomorphic (= it can run in the browser and nodejs with the same codebase).
    
  </details>
