# CRUD-Customer-registration
Customer registration operation

The complete objective of this operation is to use Css, Javascript and Html languages to assemble a CRUD that performs the four basic operations: creation, query, update and destruction of data) used in relational databases (RDBMS) provided to system users.

For this to be possible, the pages that interact with the CRUD are needed in the way the system should react, and this depends on the system (after all, there are n ways of development, and the one that has gained more strength lately is the SPA - Single Page Application thanks tools like ReactJs or VueJs), and in this case the intermediate pages take over.


For example, imagine the data flow on a screen that shows the users of a system and you need to make an interaction between the results of the database's Querys on this intermediate page (like some more complex calculation that must be done before reaching the View). so the flow would be: System requests -> intermediate page selects which CRUD pages will be used -> CRUD reads the data from the database (n reads from n tables, grouped or not (in the project, localsorage was used) ) -> Data arrives on the middle page and are processed -> processed data goes to the highest layer (either directly to the View or to the control to be reinserted in the view)

# REACT

React (also known as React.js or ReactJS) is a free and open-source front-end JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications.

### npx create-react-app my-app

it's a package runner tool that comes with npm 5.2+. Create React App doesn't handle backend logic or databases; it just creates a frontend build pipeline, so you can use it with any backend you want.

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### react advantages
Every component can be reused in new parts of your application without needing to be recreated The application is well organized and scalable, that is, easy to maintain, even as it grows in complexity and size Development is faster and cleaner;
A free and open source library;
A straight-forward learning curve, simplifying adoption;
A lightweight DOM that generally results in strong performance;
The ability to create, reuse and combine components in your code.


### o Reason for not using React in this code
The main reason, even considering React a very good tool to use, was my machine's inability to run react, having problems with the packages of babel-eslint, node-models and constant errors in the npm-start command
