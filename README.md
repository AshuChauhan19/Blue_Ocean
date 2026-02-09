📘 Blue Ocean – Backend Assignment

A Node.js backend application built using Express and MongoDB to manage Categories, SubCategories, and Courses with clean architecture and industry-standard practices.

🚀 Tech Stack

Node.js

Express.js

MongoDB (Mongoose)

Joi (Validation)

✨ Key Features

Full CRUD APIs for Category, SubCategory, and Course

Pagination, Sorting, Search, and Filtering

Soft Delete using isDeleted

Validations and business rule enforcement

Aggregation: Category → SubCategory count

Clean separation of routes, controllers, and services

📁 Project Structure
src/
 ├── routes
 ├── controllers
 ├── services
 ├── models
 ├── validations
 └── utils
 ├.env

⚙️ Setup & Run
npm install
npm run dev   # development
npm start     # production

🌐 API Base URL
http://localhost:3000/api

📦 API Modules

Category

SubCategory

Course

Each module supports:

Create

Read

Update

Soft Delete

Listing with filters

🧠 Business Rules

SubCategories must belong to a valid Category

Courses can have multiple Categories and SubCategories

All SubCategories must belong to selected Categories

Duplicate names are prevented

🛡️ Code Quality

ES6 syntax

Centralized error handling

Validation at API level

Clean and maintainable codebase

👨‍💻 Author

Ashu Chauhan
Backend Developer (Node.js)
