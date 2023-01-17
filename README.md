# RESTful-APIs
- REST is an acronym for **RE**presentational **S**tate **T**ransfer and an architectural style for distributed hypermedia systems. Roy Fielding first presented it in 2000 in his famous dissertation.

- Like other architectural styles, REST has its guiding principles and constraints. These principles must be satisfied if a service interface needs to be referred to as RESTful.


#### Tech Stack Used
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

#### To run this project on your personal machine -
- Open terminal in your corresponding project location, and -


      npm i
      npm i express
      npm i mongoose
      npm i ejs
      npm i body-parser

- **Also make sure you have [Studio 3t](https://studio3t.com/download/) and [Postman](https://www.postman.com/downloads/) installed and connected to your local machine.**
- After all the neccessary node modules are downloaded open your terminal in respective project location and - 
     ```
     mongo
     ```
- Hitting enter will connect the project to Studio 3t.
- Then, to spin-up the server - 
     ```
     nodemon app.js
     ```
- Hitting enter will start a node server on http://localhost:3000.
 
  *Note: Currently http://localhost:3000 will not display anything except `Cannot GET /` because there is not HTML included.*
- Use Postman to *get()*, *put()*, *delete()*, *patch()*.
- To explore the MongoDB functions click [here](https://www.mongodb.com/docs/).

- To clone the whole project repository to your local machine -
     ```
     gh repo clone anshulyadav01/RESTful-APIs
     ```
