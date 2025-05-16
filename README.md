
# PHP & MySQL Blog CRUD App

This is a mini blog application developed as part of my **Web Development Internship at ApexPlanet Software Pvt. Ltd.**

The project allows users to:
- ✅ Register and log in securely
- 📝 Create, Read, Update, and Delete blog posts
- 🔐 Uses password hashing and session management
- 🎨 Comes with a clean and responsive design

---

## 🚀 Features

- User Registration and Login with session tracking
- Password Hashing using PHP's `password_hash()`
- CRUD operations (Create, Read, Update, Delete) for blog posts
- Dashboard for post management
- Responsive, modern design using CSS
- Easy to run locally with XAMPP or WAMP

---

## 🗂️ Project Structure

```

blog-app/
│
├── db.php              # Database connection
├── index.php           # Login and registration form
├── register.php        # Register new user
├── login.php           # Authenticate user
├── dashboard.php       # View all blog posts
├── create.php          # Create new post
├── edit.php            # Edit existing post
├── delete.php          # Delete a post
├── logout.php          # Logout and destroy session
└── style.css           # Styling and layout

````

---

## 💽 Setup Instructions

1. Install [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/)
2. Start **Apache** and **MySQL**
3. Open **phpMyAdmin** and run:

```sql
CREATE DATABASE blog;

USE blog;

CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  username VARCHAR(255) NOT NULL UNIQUE,
  password VARCHAR(255) NOT NULL
);

CREATE TABLE posts (
  id INT AUTO_INCREMENT PRIMARY KEY,
  title VARCHAR(255) NOT NULL,
  content TEXT NOT NULL,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
````

4. Place all files inside the `htdocs/blog-app` folder
5. Open `http://localhost/blog-app/` in your browser
## 🔗 Submission Links

* 🎥 LinkedIn Video: \[Insert your LinkedIn video post URL here]
* 💾 GitHub Repository: \[Insert your public GitHub repo link here]


## 🙏 Acknowledgments

This project was completed as part of the **45-Day Internship Program** on PHP & MySQL at **ApexPlanet Software Pvt. Ltd.**

📞 Contact: +91 9905879870
🌐 Website: [https://www.apexplanet.in/internship/](https://www.apexplanet.in/internship/)


## 📌 Author

* 👤 Name:m raja sekhar
* 📧 Email:lalsarraju@gmail.com 

