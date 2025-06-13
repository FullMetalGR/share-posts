# SharePosts

**SharePosts** is a lightweight social networking application built on a custom PHP MVC framework. It features user authentication, CRUD functionality for posts, access control, and a clean, responsive Bootstrap 4 interface.

This project includes a fully custom MVC framework built from scratch using object-oriented PHP and PDO for secure, scalable development.

---

## ⚙️ Features

### Custom MVC Framework

- **Routing & Controller Dispatching:** Core library parses URLs and loads the appropriate controller and method using `.htaccess` for clean URLs.
- **Base Controller:** Simplifies loading models and views.
- **Custom PDO Wrapper:** Secure, reusable database abstraction using prepared statements.

### SharePosts Application

- **User Authentication:** Register, log in, and manage sessions.
- **Post Management:** Full CRUD (Create, Read, Update, Delete) operations for posts.
- **Access Control:** Only authorized users can create or edit their own posts.
- **Form Validation:** Server-side validation with user feedback.
- **Flash Messaging:** Simple, reusable messaging for user actions.
- **UI/UX:** Built with Bootstrap 4 for responsive, modern design.

---

## 🛠 Folder Structure

## 🛠 Folder Structure
``` 
/
├── app/
│ ├── controllers/
│ ├── models/
│ ├── views/
│ └── libraries/
├── config/
│ └── Configuration files
├── public/
│ └── index.php
├── system/
│ └── Core framework files
├── .htaccess
```
---

## 🚀 Deployment

The application is fully deployable to a production environment. Configuration files make it easy to connect to your database and update base URLs for hosting.

---

## 🧱 Technologies Used

- PHP (Object-Oriented)
- PDO (PHP Data Objects)
- Bootstrap 4
- Apache with `.htaccess` for URL rewriting

---

## 👤 User Roles & Permissions

- **Authenticated Users:** Can create, edit, and delete their own posts.
- **Guests:** Can view posts but must log in to interact.

---

## 📎 Helper Functions

Includes reusable helpers for:

- Flash messages
- URL redirection
- Input sanitization

---

## 📄 License

This project is open source and available for modification and distribution.
