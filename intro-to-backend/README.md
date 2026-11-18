# Intro to Backend: Node, Express, MongoDB CRUD API

## Setup
1. `npm install`
2. Copy `.env.example` to `.env` and fill in your MongoDB Atlas connection string
3. `npm run dev`

## Endpoints (base: http://localhost:3000)
| Method | URL                  | Description        |
|--------|----------------------|--------------------|
| POST   | /api/products        | Create a product   |
| GET    | /api/products        | List all products  |
| GET    | /api/products/:id    | Get one product    |
| PUT    | /api/products/:id    | Update a product   |
| DELETE | /api/products/:id    | Delete a product   |

Example body (JSON): `{ "name": "Laptop", "quantity": 5, "price": 799 }`
