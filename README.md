# FoodBlogWebsiteCreatedUsingReactJsMERNStack

A full-stack food blog application built with the MERN stack (MongoDB, Express.js, React.js, Node.js) for sharing and discovering delicious recipes.

# 🍳 FlavorFleet - MERN Stack Food Blog App

A full-stack web application built for food enthusiasts to discover, share, and review delicious recipes from around the world. Built using the modern MERN (MongoDB, Express.js, React.js, Node.js) stack.

![Project Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

##  Features

- **User Authentication:** Secure registration and login using JSON Web Tokens (JWT) and encrypted passwords.
- **Recipe Management:** Create, read, update, and delete (CRUD) food recipes complete with ingredients, step-by-step instructions, and images.
- **Interactive Comments & Ratings:** Users can leave feedback, rate recipes, and engage with other food creators.
- **Search & Filter:** Easily find recipes by category, ingredients, or title.
- **Responsive Design:** Fully responsive layout optimized for mobile, tablet, and desktop devices.

---

##  Tech Stack

**Client (Frontend):**
- React.js
- React Router
- Axios
- Tailwind CSS / CSS Modules

**Server (Backend):**
- Node.js
- Express.js
- Mongoose (ODM)

**Database:**
- MongoDB / MongoDB Atlas

---

## 📁 Project Structure

```text
food-blog-app/
│
├── client/                 # React frontend application
│   ├── public/
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page views (Home, RecipeDetails, CreateRecipe, etc.)
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
├── server/                 # Express backend application
│   ├── controllers/        # Route logic
│   ├── models/             # Mongoose schemas (User, Recipe, Comment)
│   ├── routes/             # API endpoints
│   ├── middleware/         # Auth & error-handling middleware
│   ├── server.js           # Entry point
│   └── package.json
│
└── .github/
    └── workflows/          # CI/CD pipelines
