📚 Library Management System

The Library Management System (LMS) is a web-based application designed to automate and simplify library operations. It helps manage books, members, and transactions efficiently, reducing manual effort and improving overall workflow.

This project provides an intuitive interface for librarians to manage the library and for users to browse, reserve, and track their borrowed books.

🚀 Key Features

📖 Book Management – Add, update, delete, and search books

👥 User Management – Register, log in, and maintain user accounts

🔄 Issue & Return – Track borrowed/returned books and manage due dates

💰 Fine Management – Calculate and maintain late return fines

🔍 Search & Filter – Quickly find books by title, author, or category

📊 Reports & History – View borrowing history and user activity

🌐 User-Friendly Interface – Simple navigation for both users and admins

🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: PHP

Database: MySQL

Additional Tools: Bootstrap (for UI styling), PHPMyAdmin (for DB management)

📂 Project Structure
Library-Management-System/
│── index.html           # Landing page
│── homepage.php         # Main dashboard
│── register.php         # User registration
│── login.php            # User login (if included)
│── books.html           # Book listing
│── cart.html            # Cart functionality
│── checkout.html        # Checkout process
│── feedbackform.php     # Feedback system
│── suggestionsform.php  # Suggestions form
│── profile.html         # User profile page
│── connect.php          # Database connection
│── scripts.js           # Frontend scripts
│── style_db.css         # DB-specific styling
│── styles.css           # Global styles
│── library video.mp4    # Demo video
│── README.md            # Documentation
└── assets/              # Images, logos, etc.

⚡ Installation & Setup

Clone the Repository

git clone https://github.com/AbhijeetRout14/Library-Management-System.git
cd Library-Management-System


Setup Database

Import the provided SQL file (if available) into MySQL using phpMyAdmin.

Update connect.php with your database credentials.

Run the Project

Place the project folder inside your local server (e.g., XAMPP → htdocs/).

Start Apache and MySQL from XAMPP.

Open in browser:

http://localhost/Library-Management-System/

📌 Future Enhancements

📲 Mobile-friendly responsive design

🔑 Role-based access (Admin, Librarian, User)

🔔 Email/SMS notifications for due books

📊 Advanced analytics dashboard

🤝 Contributing

Contributions are welcome! 🎉
If you’d like to improve this project, fork the repo and submit a pull request.

📜 License

This project is licensed under the MIT License – see the LICENSE file for details.
