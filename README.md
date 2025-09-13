# 📚 Courses API - Postman Collection

This project is a **Postman Collection** to test an API for managing courses.  
It provides a full workflow including user registration, login, and performing CRUD operations on courses.

## ✨ Features
- **Authentication**: Sign up new users and log in to get an `AccessToken`.  
- **CRUD Operations**: Create, Read, Update, and Delete courses.  
- **Postman Tests**: Validate response status codes and automatically save variables.  
- **Environment Variables**: `url`, `AccessToken`, `CourseId` for easy usage.  

## 🚀 How to Run
1. Install JSON Server with Auth:
   ```bash
   npm install -g json-server json-server-auth
2. Run the server using the database file
   ```bash
   npx json-server-auth db.json --port 3000
3. Import `collection.json` and `environment.json` into Postman and start testing.
