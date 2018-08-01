## Sigup + Login + Add profile + Logout
### ReactJS, ReactRouter4, Redux, Axios, Antd-Design, ExpressJS, MongoDB, HTTP cookie

This is a mobile SPA supporting user signup, login, logout and profile adding. Nested react components is organized by ReactRouter4. With Redux used, the complexity of managing ever-changing states such as user and conversation information is significantly decreased. Frontend sends login/signup data by sending GET or POST requests via Axios to server and backend server accesses and modifies the data in MongoDB via Mongoose. Login information is stored in cookie so that frontend can retrieve login status from server with cookie when users refresh or reload the page.

### How to run
Start MongoDB:

```sh
mongod
```


Start backend server

```sh
npm install
cd ./server
nodemon server.js
```

Start React
```sh
cd ..
npm start
```

## Screenshots

![login](https://github.com/HannahRen/signup-react/blob/master/screen%20shots/login.png?raw=true)
![logout](https://github.com/HannahRen/signup-react/blob/master/screen%20shots/logout.png?raw=true)
![profile](https://github.com/HannahRen/signup-react/blob/master/screen%20shots/profile.png?raw=true)
![signup](https://github.com/HannahRen/signup-react/blob/master/screen%20shots/signup.png?raw=true)
