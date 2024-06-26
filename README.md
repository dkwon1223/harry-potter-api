# Harry Potter Search API 🧙🏽‍♂️🪄

## 🎥 Abstract
Are you a fan of the fantastic Wizarding world of Harry Potter? This application has over 100 characters with in-depth information about them like their wands, houses, and more!

## 🎥 Contributors 
[David Kwon](https://github.com/dkwon1223)

## 🎥 Installation Instructions 
  1. Fork repository
  2. Clone repository onto your local machine
  3. `cd` into root directory of repository
  4. Run `npm install` to install project dependencies
  5. Run `node server.js` OR `nodemon server.js` to start the local server and navigate to localhost:3000

## 🎥 API Endpoints
| Description | URL | Method | Required Properties for Request | 
| ----------- | --- | ------ | ------------------------------- |
| Home        | "http:localhost:3000" | GET | none |
| Get all characters | "http:localhost:3000/api/v1/characters" | GET | none |
| Get single character | "http:localhost:3000/api/v1/characters/:id" | GET | none |
| Update entire character | "http:localhost:3000/api/v1/characters/:id" | PUT | ```json
                {                     
                name: <String>,
                gender: <String>,
                job: <String>,
                house: <String>,
                wand: <String>,
                patronus: <String>,
                species: <String>,
                bloodStatus: <String>,
                hairColor: <String>,
                eyeColor: <String>,
                loyalty: <String>,
                skills: <String>,
                birth: <String>,
                death: <String> 
                } 
                ``` |

## 🎥 Technologies Used 
![Node.js Badge](https://img.shields.io/badge/Node.js-393?logo=nodedotjs&logoColor=fff&style=flat) 
![Nodemon Badge](https://img.shields.io/badge/Nodemon-76D04B?logo=nodemon&logoColor=fff&style=flat)
![Express Badge](https://img.shields.io/badge/Express-000?logo=express&logoColor=fff&style=plastic)

## 🎥 Context
 - 🎬 Goals:
   - Gain competency with Express framework and building RESTful APIs on Node.js
 - 🎬 Wins:
   - Created my own unique RESTful API
- 🎬 Challenges:
   - It was interesting self studying different approaches on PUT/PATCH/DELETE methods as these were not covered in the curriculum!
