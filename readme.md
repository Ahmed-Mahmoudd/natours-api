# Natours API

A Node.js and Express backend API for the **Natours** tour booking application. Built as part of the [Complete Node.js Bootcamp](https://www.udemy.com/course/nodejs-express-mongodb-bootcamp/) course by Jonas Schmedtmann.

## 🚀 Features

- RESTful API for managing tours, users, reviews, and bookings
- Follows MVC architecture (Model-View-Controller)
- MongoDB + Mongoose for database and data modeling
- Express for routing and middleware
- Environment-based configuration with `dotenv`
- Centralized error handling
- API filtering, sorting, pagination, and more
- Postman collection included for testing

## 🧱 Technologies Used

- Node.js
- Express.js
- MongoDB & Mongoose
- Postman
- dotenv
- Morgan
- Nodemon

## 📁 Project Structure

```
📦natours-api
 ┣ 📂controllers
 ┣ 📂models
 ┣ 📂routes
 ┣ 📂public
 ┣ 📂views
 ┣ 📂dev-data
 ┣ 📄app.js
 ┣ 📄server.js
 ┣ 📄.gitignore
 ┣ 📄package.json
 ┣ 📄README.md
```

## 🛠 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Ahmed-Mahmoudd/natours-api.git
   cd natours-api
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file and set the following environment variables:
   ```env
   NODE_ENV=development
   PORT=3000
   DATABASE=your_mongo_uri
   DATABASE_PASSWORD=your_password
   ```

4. Run the development server:
   ```bash
   npm run start:dev
   ```

---

## 📬 Postman Collection

A Postman collection file is included:
```
natours-postman-collection.json
```

Import it into Postman to test the API endpoints.

---

## 📄 License

This project is for educational purposes and follows the structure of the Complete Node.js Bootcamp course.
