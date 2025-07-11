# GraphQL Server for Beginners

A simple GraphQL server project built by following the [freeCodeCamp GraphQL Course for Beginners](https://www.youtube.com/watch?v=5199E50O7SI&t=8s) tutorial.

This project provides a foundational understanding of GraphQL by building a basic API for managing books and authors.

## 🧰 Tech Stack

- **Node.js**
- **GraphQL**
- **GraphQL Tools**
- **Apollo Server (or express-graphql)**
- **Nodemon** (for development)

## 📁 Project Structure

```
.
├── index.js               # Entry point of the GraphQL server
├── schema.js       # GraphQL schema and resolvers
├── _db.js                 # Mock data (books, authors)
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Node.js installed:

```bash
node -v
npm -v
```

### Installation

Clone the repository:

```bash
git clone https://github.com/abelnshimiye/graphql-server-beginners.git
cd graphql-server-beginners
```

Install dependencies:

```bash
npm install
```

### Run the Server

```bash
npm nodemon index.js
```

The server will be running on:

```
http://localhost:4000
```

Use the GraphQL playground or any GraphQL client to send queries and mutations.

## 📌 Features Covered

- Creating a GraphQL schema
- Defining object types, queries, and relationships
- Querying nested fields
- Adding resolvers for data fetching
- Structuring a modular GraphQL server

## ✅ Example Queries



## 🧠 Credits

Tutorial by [freeCodeCamp.org](https://www.freecodecamp.org/).  
Video link: [GraphQL Course for Beginners](https://www.youtube.com/watch?v=5199E50O7SI&t=8s)

## 📄 License

This project is licensed under the MIT License.
