## MERN STACK | Boilerplate

### Introduction

The MERN stack is a collection of open-source technologies that are used to build full-stack web applications. It
consists of the following technologies:

MongoDB: a NoSQL document database that stores data in a flexible, JSON-like format.
Express.js: a web application framework for Node.js that provides a set of features for building web applications, such
as routing, middleware, and error handling.
React: a JavaScript library for building user interfaces.
Node.js: a JavaScript runtime that allows you to run JavaScript on the server side.
Together, these technologies allow you to build a full-stack web application using a single programming language (
JavaScript) across the entire stack.

MERN stack projects are commonly used for building dynamic web applications, such as social media platforms, e-commerce
websites, and real-time collaboration tools. The combination of MongoDB and Node.js provides a highly scalable and
flexible backend, while React provides a powerful frontend for building complex user interfaces.

Some of the benefits of using the MERN stack for web development include:

Consistency: since you're using JavaScript across the entire stack, you can avoid having to switch between different
programming languages and frameworks.
Flexibility: MongoDB's flexible data model and Node.js's non-blocking I/O architecture allow for highly scalable and
flexible backend architectures.
Developer productivity: React's component-based architecture allows for faster and more efficient development of complex
user interfaces.
Community support: the MERN stack has a large and active community of developers, which means that there are many
resources available for learning and problem-solving.

### Features

<ol>
<li>User Authentication</li>
<li>Dashboard</li>
<li>CRUD </li>
<li>Search</li>
<li>Real-time Updates</li>
<li>File Uploads</li>
<li>Payment Integration</li>
<li>Analytics</li>
<li>Localization</li>
<li>Testing</li>
</ol>

### Main Technologies/Libraries Used

<ul>
<li>React.js</li>
<li>Node.js</li>
<li>Express.js</li>
<li>Mongoose</li>
<li>Redux</li>
<li>antd</li>
<li>formik</li>
<li>react-icons</li>
<li>redux-promise</li>
<li>redux-thunk</li>
<li>yup</li>
<li>core-js</li>
<li>react-app-polyfill</li>
</ul>

## Available Scripts

In the client directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more
information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

In the client directory, you can run:

### `npm run start`

"node server.js": This script starts the server by running the server.js file using Node.js.

### `npm run dev`

"nodemon server.js": This script starts the server in development mode using Nodemon, which automatically restarts the
server when changes are made to the code.

### `npm run test`

"mocha": This script runs the unit tests for the server-side code using the Mocha testing framework.

### `npm run lint`

"lint": "eslint .": This script runs ESLint to check the server-side code for syntax errors and coding style issues.

### `npm run seed`

"seed": "node seed.js": This script seeds the database with sample data for testing and development purposes.

### `npm run build`

"build": "babel src -d dist": This script transpiles the server-side code written in modern JavaScript to a version that
is compatible with older versions of Node.js.

### `npm start:prod`

"start:prod": "npm run build && node dist/server.js": This script builds the production-ready version of the server-side
code and starts the server.

### 🗄️ Project Structure
Most of the code lives in the `src` folder of each client and server directory and looks like this:

````
.
├── client/
│   ├── public
│   ├── src/
│   │   ├── _actions
│   │   ├── _reducers
│   │   ├── components/
│   │   │   ├── views/
│   │   │   │   ├── Footer
│   │   │   │   ├── LandingPage
│   │   │   │   ├── LoginPage  
│   │   │   │   ├── Navbar
│   │   │   │   └── RegiterPage
│   │   │   ├── App.js
│   │   │   └── Config.js
│   │   ├── hoc/
│   │   │   └── auth.js
│   │   ├── index.css
│   │   └── index.js
│   ├── .gitignore
│   └── package.json
├── server/
│   ├── config/
│   │   ├── key.js
│   │   └── prod.js
│   ├── middleware/
│   │   └── auth.js
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   └── users.js
│   └── index.js
├── .gitignore
├── package.json
└── Readme.md
````