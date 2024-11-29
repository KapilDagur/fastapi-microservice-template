# **FastAPI Microservice Template 🚀**

Welcome to the **FastAPI Microservice Template**! 🎉 This repository provides a scalable and modular template for building robust microservices using **FastAPI**. It follows best practices and is designed to help developers quickly bootstrap their projects.

---

## **📑 Table of Contents**

1. [✨ Features](#-features)
2. [📂 Folder Structure](#-folder-structure)
3. [📖 Explanation of Key Folders](#-explanation-of-key-folders)
4. [🛠️ Getting Started](#️-getting-started)
5. [💡 Contributing](#-contributing)
6. [📜 License](#-license)

---

## **✨ Features**

- 🏗️ **Modular Architecture**: Organized for scalability and maintainability.
- 💾 **Database Integration**: SQLAlchemy and Alembic for ORM and migrations.
- 🌐 **API Documentation**: Auto-generated Swagger and ReDoc docs.
- 🛡️ **Custom Middleware**: For logging, authentication, and more.
- 🐳 **Docker Ready**: Containerized for seamless deployment.
- 🧪 **Test Suite**: Example unit and integration tests using pytest.

---

## **📂 Folder Structure**

Here’s the organized folder structure of the project:

```
fastapi-microservice-template/
├── app                     # 🚀 Core application directory
│   ├── alembic.ini         # ⚙️ Alembic configuration file for migrations
│   ├── controllers/        # 🧠 Handles business logic
│   ├── db/                 # 💾 Database connection and utilities
│   ├── exceptions/         # ❗ Custom exception handling
│   ├── handlers/           # 🔄 Request/Response handler utilities
│   ├── main.py             # 🔥 Entry point for the application
│   ├── middlewares/        # 🛡️ Middleware for custom processing
│   ├── migrations/         # 📜 Database migration scripts
│   ├── models/             # 🗃️ ORM models for the database
│   ├── routers/            # 🌐 API route definitions
│   ├── schemas/            # 📋 Data validation with Pydantic schemas
│   ├── setting/            # ⚙️ Configuration files for environments
│   └── utils/              # 🔧 Utility functions
├── docker-compose.yml      # 🐳 Docker Compose for service orchestration
├── Dockerfile              # 📦 Dockerfile for building the app
├── docs/                   # 📖 Project documentation
├── requirements.txt        # 📜 Python dependencies
├── scripts/                # 🛠️ Helper scripts
└── tests/                  # ✅ Test suite
```

---

## **📖 Explanation of Key Folders**

### **🚀 app/**
This is the core of the application and contains all the critical components:
- **controllers/** 🧠: Handles business logic and interactions between layers.
- **db/** 💾: Database connection setup and utilities.
- **exceptions/** ❗: Centralized custom exceptions for consistent error handling.
- **handlers/** 🔄: Utility functions for handling requests and responses.
- **middlewares/** 🛡️: Custom middleware, such as for logging or authentication.
- **models/** 🗃️: Database schemas and ORM models.
- **routers/** 🌐: API endpoints and route logic.
- **schemas/** 📋: Input and output validation using Pydantic.
- **setting/** ⚙️: Environment-specific configurations (dev, prod, test, etc.).
- **utils/** 🔧: Helper functions and reusable utilities.

---

### **📖 docs/**
Contains all documentation-related files:
- **apiref.md** 📜: Detailed API reference guide.
- **getstarted.md** 🚀: Quick start guide for users.
- **media/** 🖼️: Images or other media assets for the docs.
- **tutorials/** 📘: Step-by-step tutorials to help new users.

---

### **📜 migrations/**
Handles database schema changes using **Alembic**:
- **env.py** ⚙️: Configuration for Alembic environment.
- **versions/** 🕒: Migration scripts for database versioning.

---

### **✅ tests/**
Organized test cases to ensure quality:
- **unit/** 🧪: Unit tests for individual components.
- **module/** 🧩: Integration tests for specific modules.

---

## **🛠️ Getting Started**

1. Clone this repository:
   ```bash
   git clone https://github.com/KapilDagur/fastapi-microservice-template.git
   ```

2. Use this template to scaffold your own project by adjusting the folder structure and filling in your business logic.

---

## **💡 Contributing**

We welcome contributions! 🎉 Here's how you can help:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and test thoroughly.
4. Submit a pull request with a clear explanation of your enhancements.

---

## **📜 License**

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute as per the license terms.

---

## **Let’s Build Something Awesome Together! 🌟**

Have suggestions or need help? Open an [issue](https://github.com/KapilDagur/fastapi-microservice-template/issues) or submit a pull request.

---

### **🌐 Made with ❤️ and FastAPI**  

---