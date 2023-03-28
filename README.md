<h1 align="center">Programming Assignment</h1> 
This repository consists of MERN project, using CRUD operations

### FRONTEND development:  
  ReactJS, HTML, CSS, BOOTSTRAP 

### BACKEND development: 
  NodeJS webserver, Express web framework, mongoose 

### DATABASE management: 
   MongoDB 

___

## Libraries and frameworks used

- [Express](https://expressjs.com/) - "Fast, unopinionated, minimalist web framework for Node.js".

- [React](https://reactjs.org/) - "A JavaScript library for building user interfaces".

## Database Used

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register) - MongoDB Atlas is a global cloud database service built and run by the team behind MongoDB.

## Requirements

- [Node.js](https://nodejs.org/en/download/) >= v12


## Steps to run this project on your machine
1. Install [Node.js](https://nodejs.org/en/download/) on your machine having its version over 12.0.0
To check our node version, run this command on terminal
```
node --version       
```
2. Clone this repository on your machine
```
git clone https://github.com/Jayraj-Malamdi/mern_crud_app_employee.git
```
3. Install dependencies for front end and back end, by going into  their respective directories.
```
cd trainee_frontend
npm install
cd ../trainee_backend
npm install 
```
4. Make .env file in trainee_backend directory and your database and Port details
```
PORT=<PORT NUMBER>
MONGODB_CONNECTION_URL=mongodb+srv://<USERNAME>:<PASSWORD>@<CLUSTER NAME>.joink6c.mongodb.net/?retryWrites=true&w=majority
```
5. To run, start two terminals for each trainee_backend & trainee_frontend directory, after that runthis command
```
npm start
```


## Screenshots/Output

#### HOME PAGE: 
![Screenshot from 2023-03-28 11-26-27](https://user-images.githubusercontent.com/122361229/228188234-a00d5487-e8af-4233-a9d1-c36fd7ef1f82.png)

#### ADD NEW EMPLOYEE DETAILS PAGE: 
![Screenshot from 2023-03-28 11-30-29](https://user-images.githubusercontent.com/122361229/228188490-f026b092-af39-4416-8c43-8d7b0b85634b.png)

#### HOME PAGE AFTER ADDING NEW EMPLOYEE: 
 ![Screenshot from 2023-03-28 11-31-10](https://user-images.githubusercontent.com/122361229/228188561-00d6d2d4-c229-45ae-a33a-d7351fa62fe8.png)

#### UPDATING EMPLOYEE DETAILS: 
 ![Screenshot from 2023-03-28 11-31-38](https://user-images.githubusercontent.com/122361229/228188617-f80a9e79-ada0-4c04-9a7e-d491122641ed.png)

#### HOME PAGE AFTER UPDATING EMPLOYEE DETAILS: 
![Screenshot from 2023-03-28 11-31-57](https://user-images.githubusercontent.com/122361229/228188702-d9b1d257-0f51-4175-b27f-065c8faa62c4.png)

#### HOME PAGE AFTER DELETING EMPLOYEE DETAILS: 
 ![Screenshot from 2023-03-28 11-32-15](https://user-images.githubusercontent.com/122361229/228188762-e150a59a-e25c-4f05-8e21-4318a56f4b1c.png)

## Author

[Jayraj-Malamdi](https://github.com/Jayraj-Malamdi)
