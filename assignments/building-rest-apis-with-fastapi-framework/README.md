# 📘 Assignment: Building REST APIs with FastAPI framework

## 🎯 Objective

Build a small RESTful API using FastAPI to manage a simple resource (notes). Students will design endpoints, use Pydantic models for validation, and test the API.

## 📝 Tasks

### 🛠️ Implement API Endpoints

#### Description
Create a FastAPI application that exposes CRUD endpoints for a `Note` resource. Each `Note` should have an `id`, `title`, and `content`.

#### Requirements
Completed program should:

- Implement endpoints: `GET /notes`, `GET /notes/{id}`, `POST /notes`, `PUT /notes/{id}`, `DELETE /notes/{id}`
- Return appropriate HTTP status codes (200, 201, 204, 404, etc.)
- Use Pydantic models for request and response validation
- Provide example `curl` commands in the README showing how to call each endpoint


### 🛠️ Data Handling & Validation

#### Description
Store notes in an in-memory structure (list or dict). Add basic validation and error handling.

#### Requirements
Completed program should:

- Validate incoming data (non-empty `title` and `content`) using Pydantic
- Return clear error messages and `4xx` responses for invalid input
- Keep data in memory (persistence optional) and ensure IDs are unique


## ✅ Submission

- Place your FastAPI app in a file named `app.py` inside this assignment folder.
- Include a short `README.md` (this file) and any supporting files.
- (Optional) If you include persistence, document how to run it.


## 🔧 How to run (example)

1. Install dependencies:

```bash
pip install fastapi uvicorn
```

2. Run the app:

```bash
uvicorn app:app --reload
```

3. Example `curl` to create a note:

```bash
curl -X POST http://127.0.0.1:8000/notes -H "Content-Type: application/json" -d '{"title": "Sample", "content": "Example note"}'
```


## 📚 Learning Goals

- Understand REST API design and HTTP methods
- Use FastAPI and Pydantic for request validation
- Practice testing APIs using `curl` or HTTP clients
