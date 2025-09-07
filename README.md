Bibliothèque de Montréal · Full-Stack CRUD (React + FastAPI)

Full-stack app to manage a library: view, add, edit, delete, and search books.
Two frontends consume the same FastAPI REST API:

HTML/CSS/JS (basic interface)

React.js (Create React App + Axios)

Data is persisted in livres.json and stays in sync across both interfaces.

🚀 Local Demo

API: http://127.0.0.1:8000

React (CRA): http://localhost:3000

HTML: open frontend_html_css_js/index.html (or serve it)

✨ Features

List all books (Voir les livres)

Add a new book

Edit a book

Delete a book

Search by ID

Show total books

Book fields: id, nameLivre, auteur, bio, picture.

🧱 Tech Stack

Frontend: HTML/CSS/JS, React (CRA), Axios
Backend: FastAPI, Pydantic, Dataclasses, Uvicorn
Other: CORS, simple JSON storage

📝 License

MIT — feel free to use this project for learning and building.

👤 Author

@alejandrozambrano — “Bibliothèque de Montréal · Full-Stack (React + FastAPI)”.
