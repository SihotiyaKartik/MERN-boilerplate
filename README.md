# MERN-boilerplate
##### This repository can be used as starting code for every MERN stack project. It consist of server and client folder for backend and frontend respectively.
## Getting Started
#### Your machine should have npm(or yarn), NodeJS and MongoDB installed
## Installation
#### clone this repository using your command prompt or command line by typing following code
```js
git clone https://github.com/SihotiyaKartik/MERN-boilerplate.git
```
## Installing dependencies
#### first go to root directory which contains server and client folder and type following code
```js
npm install

```
<img src='https://github.com/SihotiyaKartik/MERN-boilerplate/blob/main/image/Screenshot%20(441).png' height='100' width='300'></img>
### Downloading server dependencies
```js
cd server
npm install
```
<img src='https://github.com/SihotiyaKartik/MERN-boilerplate/blob/main/image/Screenshot%20(442).png' height='200' width='300'></img>
### Downloading client dependencies
```js
cd client
npm install
```
<img src='https://github.com/SihotiyaKartik/MERN-boilerplate/blob/main/image/Screenshot%20(443).png' height='200' width='300'></img>
## Database
```js 
MongoDB database is used
go to server/db/database.js
you can change this "mongodb://localhost:27017/FormDatabase?readPreference=primary&appname=MongoDB%20Compass&ssl=false" or can keep this
```
### This app uses concurrently so that you don't have to run 2 different instances for server and client
```js
run following command in root directory
npm run dev
```
