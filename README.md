# 📝 Express Blog API

A simple **Blog Web Application** built using **Node.js, Express, and EJS**.
This project demonstrates how to build a RESTful API with CRUD operations and render dynamic blog posts on the frontend.

---

## 🚀 Features

* Create a new blog post
* View all blog posts
* Edit existing posts
* Delete posts
* RESTful API endpoints
* EJS templating for dynamic pages
* Clean UI with CSS styling

---

## 🛠 Tech Stack

* **Node.js**
* **Express.js**
* **EJS**
* **HTML / CSS**
* **Body Parser / Express Middleware**

---

## 📂 Project Structure

```
blog-project
│
├── public
│   └── styles
│       └── main.css
│
├── views
│   ├── index.ejs
│   └── modify.ejs
│
├── index.js
├── package.json
├── .gitignore
├── envExample.txt
├── server.js
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/blog-project.git
```

2. Navigate to the project folder

```bash
cd folder-name
```

3. Install dependencies

```bash
npm install
```

4. Start the server

```bash
node server.js
```
5. Start the Api Server (index.js)

```bash
node index.js
```

or (if using nodemon)

```bash
nodemon index.js
```

---

## 🌐 Server

The application will run at:

```
http://localhost:3000
```

---

## 📌 API Endpoints

| Method | Endpoint                | Description          |
| ------ | ----------------------- | -------------------- |
| GET    | `/`                     | View all posts       |
| GET    | `/new`                  | Create new post page |
| POST   | `/api/posts`            | Create new post      |
| GET    | `/edit/:id`             | Edit post page       |
| PATCH  | `/api/posts/:id`        | Update post          |
| DELETE | `/api/posts/delete/:id` | Delete post          |

---

## 📦 Example Post Object

```json
{
  "id": 1,
  "title": "My First Blog",
  "content": "This is my blog content",
  "author": "John",
  "date": "2026-03-14"
}
```

---

## ⚠️ Note

Currently, posts are stored **in memory** using a JavaScript array.
Data will reset when the server restarts.

Future improvements:

* MongoDB / PostgreSQL database
* Authentication
* User accounts
* Comment system

---

## 📸 Future Improvements

* Dark mode
* Rich text editor
* Image uploads
* Pagination
* Search functionality

---

## 👨‍💻 Author

Built as part of learning **Node.js and Express**.

---

⭐ If you found this project helpful, feel free to **star the repository!**
