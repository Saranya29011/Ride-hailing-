# Ride-hailing
---

# Backend Setup

### Navigate to backend

```bash
cd Backend
```

### Create virtual environment (recommended)

```bash
python -m venv venv
```

Activate it

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the backend server

```bash
uvicorn main:app --reload
```

Server will run on:

```
http://127.0.0.1:8000
```

---

# Frontend Setup

### Navigate to frontend

```bash
cd Frontend
```

### Install dependencies

```bash
npm install
```

###  Run development server

```bash
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---



