<div align="center"  width="55" height="55">
  <img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/MEDSTAR.png?raw=true" alt="html" width="120" height="120"/>
</div>

Medistar Hospital Management System is a web application built using Nodejs,Expressjs,Mongoose,Redis and MongoDB. The system is designed to automate the management of hospital appointments, including the handling of patient records, medical billing, appointment scheduling, and other administrative tasks.

The system allows users to create, read, update, and delete records of patients, doctors, and medical procedures. Patients can schedule appointments with doctors, and doctors can view their schedule and patient records. The system also includes a billing module that generates bills for medical procedures and tracks payments.

## Tech Stacks
<p align = "center">
<img src="https://github.com/PrinceCorwin/Useful-tech-icons/blob/main/images/HTML.png" alt="html" width="55" height="55"/>
<img src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS" width="50" height="55"/>
<img src="https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png" alt="js" width="50" height="50"/>
  <img src="https://raw.githubusercontent.com/tandpfun/skill-icons/59059d9d1a2c092696dc66e00931cc1181a4ce1f/icons/TypeScript.svg" alt="ts" width="50" height="50"/>
<img src="https://raw.githubusercontent.com/PrinceCorwin/Useful-tech-icons/main/images/nodejs.png" alt="nodejs" width="50" height="50"/>
<img src="https://res.cloudinary.com/kc-cloud/images/f_auto,q_auto/v1651772163/expressjslogo/expressjslogo.webp?_i=AA" alt="express" width="50" height="50"/>
 <img src="https://raw.githubusercontent.com/PrinceCorwin/Useful-tech-icons/main/images/mongodb-leaf.png" alt="mongo" width="50" height="50"/> 
<img src="https://user-images.githubusercontent.com/25181517/182884894-d3fa6ee0-f2b4-4960-9961-64740f533f2a.png" alt="redis" width="50" height="50"/>
<img src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" alt="npm" width="50" height="50"/>
  
</p>
<hr>

## Features 
-  Authentication
-  APIValidation
-  Responsive
-  Cross Platform
-  Signup/signin/Logout
-  Appointment Booking 
-  Appointment Cancelation
-  Admin can perform all crud operations

## Run Locally
### Clone this Project

```
https://github.com/faraz412/cozy-passenger-4798.git
```

### Install npm Packages

```javascript
npm i --global
```

### Go to Backend Folder
```javascript
cd backend
```

### Run Server
```javascript
npx nodemon index.js
```
### Runs the project in the development mode

[http://localhost:8080](http://localhost:8080)


### Environment Variables Required
`mongoURL`

`key`

`PORT`

`Redis Cloud Password + Host + Port`

`Nodemailer Password`

## NPM Packages
<p align = "center">
<img src="https://repository-images.githubusercontent.com/139898859/9617c480-81c2-11ea-94fc-322231ead1f0" alt="bcrypt.png" width="70" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/cors.png?raw=true" alt="cors" width="70" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/download.png?raw=true" alt="dotenv" width="70" height="50"/>
<img src="https://github.com/faraz412/cozy-passenger-4798/blob/main/Frontend/Files/JWT.png?raw=true" alt="jwt" width="70" height="50"/>
<img src="https://4008838.fs1.hubspotusercontent-na1.net/hubfs/4008838/mogoose-logo.png" alt="mongoose.png" width="70" height="70"/>     
<img src="https://i0.wp.com/community.nodemailer.com/wp-content/uploads/2015/10/n2-2.png?fit=422%2C360&ssl=1" alt="nodemailer" width="50" height="70"/>
<img src="https://user-images.githubusercontent.com/13700/35731649-652807e8-080e-11e8-88fd-1b2f6d553b2d.png" alt="nodemon.png" width="50" height="50"/>
<img src="https://www.npmjs.com/npm-avatar/eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhdmF0YXJVUkwiOiJodHRwczovL3MuZ3JhdmF0YXIuY29tL2F2YXRhci8wNmFkMDUxNjc0NDA0NTVjOTQzYzE4NWIwNmM4NjBmMD9zaXplPTEwMCZkZWZhdWx0PXJldHJvIn0.fJ4Me0BC-QzMrHKVqZzMx9CzgTcYb06jEt9nk9NxC2c" alt="otpgen.png" width="50" height="50"/>
<img src="https://user-images.githubusercontent.com/25181517/182884894-d3fa6ee0-f2b4-4960-9961-64740f533f2a.png" alt="redis" width="50" height="50"/>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKZRJJRPM1V6XKXBLn2fnsy5VwmLW1uO9ixCfCYiZRwWeLKe2ukB17uzxRRyhZElgzn_E&usqp=CAU" alt="twilio" width="70" height="50"/>
</p>


## Frontend Part
- Home page
- Signup/Login
- Logout
- Book appointment
- Make a payment
- Feedback

## Backend Part
- Authentication using JWT
- Storing password by hasing it
- Mongoose - connecting the database
- Server side -> Node.js and Express 
- Nodemailer - sending Emails
- Blacklisting of tokens

    
## API Endpoints
   #### Welcome
```javascript
GET  /api/
```
  #### Email Verification
```javascript
POST  /api/user/emailVerify
```
  #### User Signup
```javascript
POST  /api/user/signup
```
  #### User Signin
```javascript
POST  /api/user/signin
```
  #### User Logout
```javascript
POST  /api/user/logout
```
  #### Doctor 
```javascript
GET /api/doctor/allDoctor
GET /api/doctor/search?
GET /api/doctor//allDoctor/:id
GET /api/doctor/docPending
DELETE /api/doctor/removeDoctor/:id
POST /api/doctor/addDoctor
PATCH /api/doctor/updateDoctorStatus/:id
PATCH /api/doctor//isAvailable/:doctorId
```
  #### Appointment Booking  
```javascript
GET /api/appointment/allApp/
GET /api/appointment/getApp/:appointmentId
GET /api/appointment/checkSlot/:doctorId
POST /api/appointment/create/:doctorId
POST /api/appointment//deleteSlot/:doctorId
DELETE /api/appointment/cancel/appointmentId
PATCH /api/appointment/reschedule/:appointmentId
```
  #### Appointment Admin CRUD Operations
 ```javascript
 GET /api/appointment/all/
 GET /api/appointment/allPending
 DELETE /api/appointment/reject/:appointmentId
 PATCH /api/appointment/approve/:appointmentId
 ```
<!-- 
 ### 
`USERS DATA...`

    {"first_name":"harsh thakur",
    "last_name":"thakur",
    "email":"harsh@gmail.com",
    "mobile":"909999345",
    "password":"123456"  }

 ### 
`DOCTORS DATA...`

    {"doctorName":"Abhishek Jaiswal",
    "email":"abhisek@gmail.com",
    "qualifications":"MBBS from AIMS Delhi",
    "experience":"14 years of experience",
    "phoneNo":"7011144555",
    "city":"Mumbai",
    "departmentId":1,
    "status":true,
    "isAvailable":true;
    "image":"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJO1Bmu2stkBmmOJXmyHN5G7UHmeA4xr5z0whR9JZF&s" }

 ### 
`APPOINTMENT DATA...`

    {"patientId":"64256f28b1fc4d36b5a12be7",
    "doctorId":"6425319914291e303a3cf2c4",
    "ageOfPatient":40,
    "gender":"male",
    "address":"Mumbai woribali",
    "problemDescription":"having some problem related to neourology ",
    "appointmentDate":"30-03-2023",
    "createdAt":,
    "updatedAt":,
    "paymentStatus":false} -->
     
 ## Project Highlights  
 
![image](https://user-images.githubusercontent.com/109690823/229313097-98ac03fb-69b0-4833-849c-48c4a1b9d38d.png)
![image](https://user-images.githubusercontent.com/109690823/229355448-be996d1e-8545-44e1-b1ba-dc3d62d0ac9a.png)
![image](https://user-images.githubusercontent.com/109690823/229355506-3ae1da89-9434-4400-9ab2-b8b9f86e67aa.png)
![image](https://user-images.githubusercontent.com/109690823/229355596-5bfd0bf9-9147-47fb-bb42-b6e04ac4208b.png)

## Demo
```

```

## Authors

- [@faraz412](https://github.com/faraz412)
- [@deepakChourasiya-aj](https://github.com/deepakChourasiya-aj)
- [@abhishek1494k](https://github.com/abhishek1494k)
- [@Atul3007](https://github.com/Atul3007)
- [@prernadave](https://github.com/prernadave)



