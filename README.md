# 🧪 JSONPlaceholder API Testing — QA Portfolio

A comprehensive API test collection built with Postman, 
covering full CRUD operations and negative test scenarios.

## 📌 Endpoints Covered
- **Posts** — GET, POST, PUT, DELETE
- **Comments** — GET, filter by post ID
- **Users** — GET, nested resources (todos, albums)
- **Albums & Photos** — GET, filter by album
- **Todos** — GET, filter by status
- **Negative Tests** — 404, invalid input, edge cases

## 🛠️ Tools Used
- Postman (API Testing)
- JSONPlaceholder (Mock REST API)
- JavaScript (Test Scripts)
- Postbot (AI Test Generator)

## ▶️ How to Run
1. Import `collection.json` into Postman
2. Set environment variable `baseurl` = `https://jsonplaceholder.typicode.com`
3. Run the collection using Collection Runner

## 📊 Test Coverage
- ✅ Status code validation
- ✅ Response body structure validation  
- ✅ Data type validation
- ✅ Error handling & edge cases
