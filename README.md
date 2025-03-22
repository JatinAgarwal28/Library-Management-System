# 📚 Library Management System

A **Python Flask-based Library Management System** with **MongoDB Atlas** integration. This project allows users to register, log in, and manage books efficiently, providing an interactive and user-friendly experience.

## 🚀 Features

- **User Authentication**: Secure user registration and login.
- **Book Management**: Add, update, delete, and view books.
- **MongoDB Atlas Integration**: Cloud-based database for efficient storage.
- **Interactive UI**: Built with Flask and HTML/CSS.
- **RESTful API Endpoints**: Enables easy interaction with the system.

## 🛠 Tech Stack

- **Backend**: Flask (Python)
- **Database**: MongoDB Atlas
- **Frontend**: HTML, CSS, JavaScript
- **IDE**: VS Code

## 📂 Project Structure
```
Library-Management-System/
│-- static/             # CSS, JavaScript, images
│-- templates/          # HTML templates
│-- app.py              # Flask application
│-- config.py           # Configuration settings
│-- requirements.txt    # Dependencies
│-- README.md           # Project documentation
```

## 🎯 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up MongoDB Atlas connection**
   - Create a `.env` file and add your MongoDB Atlas URI:
   ```
   MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/library_db
   ```

5. **Run the application**
   ```bash
   python app.py
   ```

6. **Access the application**
   Open your browser and go to `http://localhost:5000`

## 🔗 API Endpoints

| Endpoint      | Method | Description |
|--------------|--------|-------------|
| `/`          | GET    | Render login page |
| `/login`     | POST   | User login |
| `/register`  | GET, POST | User registration |
| `/home`      | GET    | User dashboard |
| `/books`     | GET    | View all books |
| `/books/add` | POST   | Add a new book |
| `/books/<id>/edit` | PUT | Edit book details |
| `/books/<id>/delete` | DELETE | Delete a book |

## 🤝 Contributing
Contributions are welcome! Please fork this repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License.

---

🚀 **Happy Coding!**

