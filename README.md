# Placement Portal 💼

A MERN stack web app designed for NIT Patna's placement process. It allows placement coordinators to create and manage company profiles, streamlining job information distribution for students.
- **Live Link**: [Visit the Placement Portal](https://placement-portal-by-om.netlify.app/) 🌐

<br>

## Table of Contents 📑
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

<br>

## Introduction 📝

The **Placement Portal** is a MERN stack web application designed to streamline the placement process for students and placement coordinators at NIT Patna. 🌐 This platform eliminates the need for multiple WhatsApp groups by centralizing job-related information. Coordinators can create detailed company profiles with job descriptions, CTC, stipend, eligibility criteria, and more. Students can easily access the details of available job opportunities through a clean and intuitive interface. 

<br>

## Features ✨

1. **User Authentication 🔐**:  
   - Secure login and registration system using **JWT** for placement coordinators.
   - Two user roles: **Admin/Coordinator** and **Student** to differentiate functionalities.

2. **Company Profile Management 🏢**:  
   - Coordinators can add and update company details such as **CTC**, **stipend**, **job roles**, and **eligibility criteria**.
   - Allows easy **CRUD** operations (Create, Read, Update, Delete) on company profiles. 🔄

3. **Job Listings 📃**:  
   - Students can browse and view detailed job postings.
   - Each job posting includes **CTC**, **stipend**, **roles**, **location**, and more! 🌍

4. **Search & Filter 🔍**:  
   - Students can quickly find job listings using filters for **role**, **location**, **CTC range**, and more.  
   - Easy-to-use **search bar** to find relevant positions! 💼

5. **Responsive Design 📱**:  
   - The platform adapts to all screen sizes, ensuring a smooth experience on both **desktop** and **mobile devices**. 📱💻

6. **Real-Time Updates 🔄**:  
   - Coordinators can post job updates in real-time, which students can access instantly. ⏳

7. **Secure Access 🔒**:  
   - **JWT** based authentication ensures secure and reliable login for coordinators. 🛡️

8. **Easy Navigation 🧭**:  
   - Clean, intuitive navigation for both **students** and **coordinators**. Everything you need is just a click away! 🖱️

9. **Job Application Links 🔗**:
   - Each job posting includes a link to apply directly to the company's official portal. 🚀
  
10. **Dashboard 📊**:
    - Coordinators can manage job listings and track their status on the dashboard.
    - Students can easily view the latest job openings from the **student dashboard**.
<br>

## Technologies Used ⚙️

- **Frontend 🖥️**:  
  - React.js ⚛️  
  - React Router 🔄  
  - Tailwind CSS 🌈  
  - Axios 🌐  

- **Backend 🔧**:  
  - Node.js 🚀  
  - Express.js ⚙️  
  - MongoDB (via Mongoose) 🍃

- **Authentication 🔑**:  
  - JSON Web Token (JWT) 🔒 for secure login

- **Database 💾**:  
  - MongoDB (NoSQL Database for flexible data management)

- **Deployment 🌍**:  
  - Render for backend
  - Netlify for frontend  
<br>

## Installation ⚡

### Prerequisites 🧑‍💻
- [Node.js](https://nodejs.org/en/) (>=14.x)
- [MongoDB](https://www.mongodb.com/try/download/community) (locally or use MongoDB Atlas for cloud-based database)
<br>

### Steps to Install Locally 🚀

1. **Clone the repository**:
   ```bash
   git clone https://github.com/omraj0/placement-portal.git
   cd placement-portal
   ```

2. **Set up the backend**:
- Navigate to the backend directory and install dependencies:
   ```bash
   cd backend
   npm install
   ```
   
- Create a .env file in the backend directory and add the following:
   ```bash
   MONGO_URI=your_mongodb_connection_url
   JWT_SECRET=your_secret_key
   PORT=5000
   ```
   
- Run the backend server:
   ```bash
   npm start
   ```
   
3. **Set up the frontend**:
- Navigate to the frontend directory and install dependencies:
  ``` bash
  cd frontend
  npm install
  ```
  
- Run the frontend server:
  ```bash
  npm start
  ```
<br>

## Usage 🖱️

### Coordinator Login 👨‍🏫
1. Coordinators can **sign up** and **log in** via the login page.
2. After logging in, they can **add** and **manage company profiles** with job details such as CTC, stipend, roles, and more.
3. Coordinators can easily **update** or **delete** job listings from the dashboard.

### Student Access 🎓
1. Students can **view job listings** and **apply** using the provided application links.
2. They can **search** and **filter** through job postings to find the best match based on roles, locations, and more.

### Dashboard 📊
1. **Coordinators** can manage and organize job listings from their **dashboard** with easy CRUD operations (Create, Read, Update, Delete).
2. **Students** can **see an overview** of available opportunities and apply directly from the dashboard.

<br>

## Contributing 🤝

We welcome contributions to the Placement Portal! Here's how you can help:

1. **Fork** the repository and clone it to your local machine:
   ```bash
   git clone https://github.com/your-username/placement-portal.git
   ```
   
2. **Create a new branch**:
   ```bash
   git checkout -b feature/your-feature
   ```

3. **Make changes and commit them**:
   ```bash
   git commit -am 'Add a new feature'
   ```

4. **Push the changes to your forked repository**:
   ```bash
   git push origin feature/your-feature'
   ```

5. **Create a Pull Request** to merge your changes into the main repository.
<br>

## Issues 🐞
Feel free to **open an issue** if you encounter any bugs or have suggestions for improvements. We encourage you to submit feature requests or improvements to enhance the project!

<br>

## License 📄
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.
<br>

## Contact 📫
- **Portfolio**: [Visit Portfolio](https://omraj0.github.io/) 🌐  
- **Email**: [omraj010@gmail.com](mailto:omraj010@gmail.com) ✉️

