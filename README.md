# Simple Social

A minimal **full-stack social media application** built to understand how real-world apps work end-to-end — from authentication to media uploads to frontend–backend integration.

This project allows users to **sign up, log in, and create posts with images and videos**.

---

## 🚀 Features

* User authentication (signup & login)
* JWT-based protected routes
* Create posts linked to authenticated users
* Upload images **and videos**
* Async backend with clean project structure
* Simple frontend for interaction

---

## 🛠 Tech Stack

### Backend

* **FastAPI** – API framework
* **fastapi-users** – Authentication & JWT handling
* **SQLAlchemy (Async)** – ORM
* **SQLite** – Database
* **ImageKit** – Image & video uploads

### Frontend

* **Streamlit** – UI for authentication & post creation

---


## ⚙️ Setup & Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/UtkarshGoliya/Simple-Social.git
cd Simple-Social
```

### 2️⃣ Create & activate virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Environment Variables

Create a `.env` file and add your **ImageKit credentials**:

```
IMAGEKIT_PUBLIC_KEY=your_public_key
IMAGEKIT_PRIVATE_KEY=your_private_key
IMAGEKIT_URL_ENDPOINT=your_url_endpoint
```

---

### 5️⃣ Run the backend

```bash
python main.py
```

### 6️⃣ Run the frontend

```bash
streamlit run frontend.py
```

---


## 🙏 Credits

This project is **inspired by Tech With Tim’s YouTube tutorial**.
I used it as a base to deeply understand the architecture by building, debugging, and running the app myself.
