# CS-465-Travlr_Getaways

# 1. Architecture

## 1A. Compare and contrast the types of front-end development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

Express HTML is a backend framework for Node.js, which is not directly used for front-end development. It's commonly used to create APIs, manage routes, and serve static files. JavaScript was used for the front-end development to create dynamic and interactive elements in the web pages. Single-Page Application (SPA) is a modern approach where the entire application resides on a single web page, and dynamic content is loaded as users interact with the app. AngularJS is an example of a front-end framework for building SPAs.

## 1B. Why did the backend use a NoSQL MongoDB database?

The backend uses a NoSQL MongoDB database due to its flexible schema, which allows for easy storage and retrieval of JSON-like data. In a full-stack application, this flexibility is advantageous because the front-end and back-end can communicate using JSON, and the data can be stored in MongoDB as BSON (a binary representation of JSON). MongoDB also provides horizontal scalability, making it suitable for handling large amounts of data and concurrent users.

# 2. Functionality

## 2A. How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON (JavaScript Object Notation) is a data interchange format often used for API communication while JavaScript is a programming language that can manipulate data, control the UI, and interact with APIs. JSON ties the front-end and back-end by serving as the format for data exchanged between them. APIs send JSON responses to front-end requests, which JavaScript can then process and use to update the UI.

## 2B. Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components.

When building the client-side of this application I found that there was a lot of redundant code included between a couple of different web pages. To remedy this, handlebars were used to create sections that were inserted onto the necessary web pages. Code refactoring involves restructuring existing code to improve readability, maintainability, and performance. Reusable UI components are modular pieces of UI that can be reused across different parts of an application. The benefits of reusable UI components include consistency, efficiency, maintenance, and scalability.

# 3. Testing

## 3A. Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full-stack application.

API testing involves validating API endpoints' functionality, including requests and responses.
Testing with security layers involves ensuring that authentication and authorization mechanisms work as intended. Types of API testing include unit testing, which deals with individual components, integration testing, which deals with interactions between components, and end-to-end testing which deals with the entire application. Methods (GET, POST, PUT, DELETE) define actions that can be performed on resources. Endpoints are URLs where these methods can be accessed, serving as entry points to the application. Security involves mechanisms like authentication (verifying identity) and authorization (granting access rights) to ensure data protection and user privacy.

# 4. Reflection

## 4A. How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

The course has provided skills in full-stack development, including frontend, backend, databases, and API interactions. The skills I’ve learned include a few front-end skills like HTML, CSS, JavaScript, and AngularJS. A few backend skills like Express, Node.js, MongoDB. As well as API development and testing. These skills enhance marketability by making me capable of contributing to both frontend and backend development, understanding the entire application lifecycle, and being adaptable to various roles in web development.
