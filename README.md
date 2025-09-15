# 📚 Courses API

## 🔎 Overview

This project is a RESTful API for managing courses, built with **Node.js** and **Express**, using a JSON file (`db.json`) as a mock database.
It supports user authentication and CRUD operations for courses.
The API is tested using **Postman**, with a comprehensive collection of test cases.

## ✨ Features

* 🔐 **User Authentication**: Login endpoint to generate an access token.
* 📖 **Course Management**:

  *  Create a new course.
  *  Retrieve a single course by ID.
  *  Update an existing course.
  *  Delete a course.
  *  Retrieve all courses.
*  **Testing**: Postman collection with automated tests ✅.

## 🛠️ Prerequisites

*  **Node.js**: Version 14.x or higher.
*  **Postman**: For testing the API endpoints.
*  **npm**: For installing dependencies.

## 🚀 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/courses-api.git
   cd courses-api
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the server:

   ```bash
   npm start
   ```

   The server will run on 🌍 `http://localhost:3000`.

## 🗂️ Database

* **Courses**: `id`, `title`, `description`.
* **Users**: `email`, `password` (hashed), and `id`.

## 📡 API Endpoints

* **POST /login** 
* **POST /660/courses** 
* **GET /660/courses/\:id** 
* **PUT /660/courses/\:id** 
* **DELETE /660/courses/\:id** 
* **GET /660/courses** 

## 🧪 Testing with Postman

1. Import `collection.json` and `environment.json`.
2. Set the `url` variable.
3. Run the "Positive Test" collection.

## 📂 Project Structure

* `db.json` – Mock database
* `collection.json` – Postman test cases
* `environment.json` – Postman environment variables

## 📝 Notes

* All course-related endpoints require **Bearer token**.
* Passwords are hashed.
* Tests expect predefined course titles.
