# 🎓 Full Stack Open Course Solutions
This repository serves as a **personal collection of my solutions, exercises, and projects** completed during the **University of Helsinki's Full Stack Open** course.

The course is a deep dive into modern web application development using **JavaScript/TypeScript**, focusing on building single-page applications (SPA) with **React** and powerful REST APIs with **Node.js** and **Express**.

-----

## 💻 Tech Stack & Key Topics

The Full Stack Open course covers a comprehensive modern web development stack:

| Category | Technology/Topic |
| :---: | :--- |
| **Frontend** | **React**, **Redux**, React Router, Custom Hooks, Styling (CSS/Webpack), React Native |
| **Backend** | **Node.js**, **Express**, **REST APIs**, **GraphQL** |
| **Databases** | **MongoDB** (NoSQL), Relational Databases (**SQL**) |
| **Development**| **Testing** (Frontend & Backend), **TypeScript**, Containerization (**Docker**), **CI/CD** |

-----

## 📁 Repository Structure

The exercises are organized into directories matching the course structure. Each part has its own folder, and exercises within that part may be further grouped into sub-directories (e.g., `unicafe`, `phonebook`).

```
.
├── part0/
│   ├── newnotediagram
│   ├── SPAdiagram
│   └── newnoteinSPAdiagram
├── part1/
│   ├── courseinfo/
│   ├── unicafe/
│   └── anecdotes/
├── part2/
│   ├── phonebook/
│   └── countries/
├── part3/
│   └── (node/express backend)
├── part4/
│   └── (blog list backend)
...
└── README.md
```

-----

## 🚀 Getting Started (Run Locally)

Since the exercises cover different parts of the stack (frontend and backend), the setup process will vary.

### Frontend Applications (e.g., Part 1, 2, 5)

To run a specific **React application** (e.g., exercises from `part1/unicafe`):

```bash
# 1. Navigate to the project directory
cd part1/unicafe

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
# or npm start, depending on the project

# Open your browser to http://localhost:5173 (or the port indicated in the terminal).
```

### Backend Applications (e.g., Part 3, 4)

Backend projects typically require **Node.js** and an environment variable file (`.env`).

```bash
# 1. Navigate to the project directory
cd part3

# 2. Install dependencies
npm install

# 3. Create a .env file
# Define your database URI and port in a .env file in the root of the project:
# Example for MongoDB:
# MONGODB_URI=mongodb://localhost:27017/my-database
# PORT=3001

# 4. Start the server
npm run dev
# or npm start
```

-----

## ✨ Course Parts Overview

Here are the main topics covered in the course, part by part:

| Part | Topic | Focus |
| :---: | :--- | :--- |
| **Part 0** | Fundamentals of Web Apps | Environment setup, Git, Debugging, **HTTP requests**. |
| **Part 1** | Introduction to React | **Components**, Props, **Component State**, Event Handlers. |
| **Part 2** | Communicating with Server | Forms, **Fetching data from a REST API**, Effect Hooks. |
| **Part 3** | Programming a Server | **Node.js**, **Express**, **MongoDB**, REST API Deployment. |
| **Part 4** | Testing Express Servers | Unit and Integration **Testing** for the backend, User Administration. |
| **Part 5** | Testing React Apps | Component testing with React Testing Library and End-to-End testing. |
| **Part 6** | Advanced State Management | **Redux**, Redux Toolkit, React Query. |
| **Part 7** | React Router, Hooks, Webpack | Routing, custom hooks, and application styling. |
| **Part 8** | GraphQL | Implementing and consuming a **GraphQL API**. |
| **Part 9** | TypeScript | Adding **static typing** to React and Node applications. |
| **Part 10** | React Native | Introduction to **mobile development**. |
| **Part 11** | CI/CD | Continuous Integration and Deployment practices. |
| **Part 12** | Containers | **Docker** and containerization. |
| **Part 13** | Relational Databases | Postgres, **SQL**, and Object-Relational Mappers (ORM). |

-----

## 📝 License

The course materials are licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. My solutions in this repository are intended for personal learning and are shared under the **MIT License**.

-----

Let me know if you complete a project and want to add a section for deployment links or project highlights\!
