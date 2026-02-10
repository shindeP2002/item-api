# Item Management REST API

Simple Java Spring Boot backend for managing items (like Flipkart products).

## Endpoints

### Add Item
POST `/api/items`

```json
{
  "name": "Laptop",
  "description": "Gaming Laptop",
  "price": 55000
}
```

### Get Item By ID
GET `/api/items/{id}`

Example:
`GET /api/items/1`

## Run Locally

```bash
mvn spring-boot:run
```

Server runs at:

http://localhost:8080
