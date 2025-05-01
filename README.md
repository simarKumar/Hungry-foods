# Hungry-foods
HungryFood is a full-stack food ordering website built using Node.js, Express, and MySQL. It allows users to browse restaurants, view menus, add items to their cart, and place orders. The system includes user authentication, admin restaurant management, and a responsive interface for an improved user experience.

# 🍔 HungryFood – Food Ordering Website

HungryFood is a full-stack food ordering web application that allows users to browse restaurants, explore menus, add items to their cart, and place online orders. Built using Node.js, Express, MySQL, and EJS, the project includes admin and user roles, authentication, and basic restaurant management.

---

## 🚀 Features

- 🔐 User authentication (login/register)
- 🏪 Restaurant listing and menu browsing
- 🛒 Add to cart and place orders
- 📦 Admin panel for restaurant and menu management
- 📊 Order history and user profile
- 🎨 Responsive UI using HTML/CSS and EJS templating

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, EJS (Embedded JavaScript Templates)
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Authentication**: express-session, bcrypt
- **Other Tools**: XAMPP, VS Code

---

## 📂 Project Structure
food-ordering-website/ │ ├── app.js # Main Express app ├── bin/www # Server startup script ├── routes/ # Route handlers ├── views/ # EJS templates ├── public/ # Static assets (CSS, JS, images) ├── models/ # Database queries └── config/ # DB configuration

## ⚙️ Setup Instructions

### 1. Clone the Repository
``bash
git clone https://github.com/your-username/food-ordering-website.git
cd food-ordering-website

2. Install Dependencies
npm install

3. Setup MySQL Database
Start MySQL using XAMPP

Create a database (e.g., hungryfood)

Import the provided SQL file (if any)

4. Configure Database
Edit config/db.js or app.js to match your MySQL credentials:

js
host: 'localhost',
user: 'root',
password: '',
database: 'hungryfood'
5. Start the Server

npm start
Then open http://localhost:3000 in your browser.

📸 Screenshots
![hungryfoods](https://github.com/user-attachments/assets/ef3413e6-f676-40a6-8ff1-cf62516f980b)


📃 License
This project is for educational purposes only. Feel free to fork and customize it!

🙋‍♀️ Author
Simar Kumar  – Final Year B.E. CSE Student Chitkara University
