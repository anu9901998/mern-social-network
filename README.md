# MERN Social Network




Features implemented: user authentication, profile viewing, posting, commenting, and following/unfollowing.




### Potential improvements:

- Add option for user to post images
- Add option for user to change their avatar/background to a custom image
- Add social media login options (e.g. Facebook, Google, Twitter)
- Implement find users feature (i.e. find users by typing their name into a search field)
- Improve code organization
- Write more tests

## Setup instructions 

First install the dependencies:

1. Clone the repository.
2. `cd` into the directory and run `npm install`.
3. Run `cd client && npm install`.

Next, set up the database credentials:

1. Log into or create an [MongoDB Atlas]
2. Create a new MongoDB cluster. You can go with the default settings or customize them as you wish. Once the cluster is created, click "Connect."
  
3. Whitelist a connection IP address and create a new MongoDB user.

4. Once connection security is set up, choose "Connect Your Application."
   
5. Replace the dbURI in `secrets.js`, located in backend folder, with the connection string. Replace `dbname`, and `<password>` with the user and password you created in step 2.
  
6. `cd` back into the main directory and run `npm start`. You can access the site at `localhost:3000`.



## Built With

- [Express.js](https://expressjs.com/) - Backend web framework
- [JSON Web Token](https://jwt.io/) - A standard to securely authenticate HTTP requests
- [Material-UI](https://material-ui.com/) - UI library for React
- [MongoDB](https://www.mongodb.com/) - Database to store document-based data
- [Mongoose](https://mongoosejs.com/) - Object-modeling tool for Node.js
- [Node.js](https://nodejs.org/en/) - Runtime environment to help build fast server applications
- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Redux](https://redux.js.org/) - JavaScript library to help better manage application state

## Acknowledgments

- Design was inspired by preexisting projects like Qolzam's [React Social Network](https://github.com/red-gold/react-social-network) and Shama Hoque's [Mern Social](https://github.com/shamahoque/mern-social).
- Authentication was implemented with the help of Krunal Lathiya's [example](https://appdividend.com/2018/07/18/react-redux-node-mongodb-jwt-authentication/#React_Redux_Node_MongoDB_JWT_Authentication), Brad Traversy's [guide](https://www.youtube.com/watch?v=Z1ktxiqyiLA) on building a login system, and Maximilian Schwarzmüller's [guide](https://www.youtube.com/watch?v=0D5EEKH97NA) on JWT (primarily episodes 11 and 12).
- Restful CRUD API builds on concepts explained in Andrew Mead's [Node.js course](https://www.udemy.com/the-complete-nodejs-developer-course-2/).
- [Material-UI](https://material-ui.com/getting-started/installation/), [React](https://reactjs.org/docs/getting-started.html), [Redux](https://redux.js.org/introduction), [Mongoose](https://mongoosejs.com/docs/guide.html) documentation.
