# Food sharing recipe 

## Screenshots 
![website1](https://github.com/user-attachments/assets/7c3767f4-3502-4a59-8555-674ca2883e55)

![website2](https://github.com/user-attachments/assets/b4527f7a-3fee-4d80-9397-08b766f5c3cd)

![website3](https://github.com/user-attachments/assets/c429b939-20c0-4c42-888b-39544dea8785)

![website4](https://github.com/user-attachments/assets/43edac97-df74-4ba7-a4c3-d2844d8f6ee6)

## Features
1. **User Authentication**: Secure user authentication and registration system.
2. **Recipe Management**: Create, edit, and delete your recipes.
3. **Recipe Discovery**: Browse and search for recipes shared by other users.
4. **Comments and Ratings**: Leave comments and rate recipes.
5. **Favorite Recipes**: Save your favorite recipes for easy access.
6. **Responsive Design**: Works seamlessly on both desktop and mobile devices.

## User Authentication: Secure user authentication and registration system.

 Navigate to server folder:

       cd server

Create a `.env` file in the project root and configure your environment variables:
   
       PORT=2000
       MONGODB_URI=mongodb://localhost/recipe-app
       SECRET=your-secret-key

Replace `your-secret-key` with a secure secret for JWT token generation.

Start the development server

       node index.js


## Folder Structure
The project follows a standard MERN stack folder structure:

- client: Contains the React frontend application.
- server: Contains the Express.js backend application.
- Schema: Define the MongoDB schemas and models.
- routes: Define the API routes.
- controllers: Handle route logic and interact with the database.
- middlewares: Custom middleware functions.
- db: Configuration files (e.g., database connection).

## Technologies Used
#### Frontend:

- React

#### Backend:

- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Tokens (JWT) for authentication
- bcrypt for secured password hashing



