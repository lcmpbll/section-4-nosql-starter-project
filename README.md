# Help Queue

## By Liam Campbell and Derrak Richard

## A help ticket creator for it issues.

## Technologies Used

* React.js
* Firebase/FireStore
* Node.js
* CSS
* Babel
* Es-Linter


## Description

_A user can sign in and sign up then enter information into a help queue ticket. The ticket takes input such as their name, their location and the issue they are experiencing. The information is then sent to a firestore database that adds a timestamp and orders all of the available help tickets by time created. The tickets may be updated and deleted._

## Installation and Setup

* Clone this repository from git hub to your local machine. 

* Set up a firebase project at https://console.firebase.google.com/

* `$ npm install` in the top directory of the project.

* Create a .env file in the top level of this project and insert the following...

<pre>
REACT_APP_FIREBASE_API_KEY = "YOUR-UNIQUE-CREDENTIALS"
REACT_APP_FIREBASE_AUTH_DOMAIN = "YOUR-PROJECT-NAME.firebaseapp.com"
REACT_APP_FIREBASE_PROJECT_ID = "YOUR-PROJECT-FIREBASE-PROJECT-ID"
REACT_APP_FIREBASE_STORAGE_BUCKET = "YOUR-PROJECT-NAME.appspot.com"
REACT_APP_FIREBASE_MESSAGING_SENDER_ID = "YOUR-PROJECT-SENDER-ID"
REACT_APP_FIREBASE_APP_ID = "YOUR-PROJECT-APP-ID"
</pre>

* Replace all quoted items with your individual data found in the firebase settings of your project. 

* `npm run start` in the top level of your directory. 
---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### Check it out 
 
_This application is hosted at https://help-queue-887ce.firebaseapp.com/_

## Known Bugs

* styles don't appear on hosted site

### License 

[Copyright](LICENSE)  (c) 09/20/2022 Liam Campbell

### Contact Information

_Feel free to reach out via [github](https://github.com/lcmpbll/)_