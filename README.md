# SequelFlow: AI-Powered SQL Assistant Web App

**SequelFlow** is a modern, user-friendly web application designed to simplify database interactions by converting natural language queries into accurate SQL statements. Built with a robust tech stack, it offers schema exploration, query history, and seamless SQLite database integration, empowering users to interact with data effortlessly.

---

## 🌟 Key Features

- **Natural Language to SQL Conversion**: Transform plain English queries into precise SQL statements using advanced AI via the OpenRouter API.
- **Interactive Schema Explorer**: Visualize and explore SQLite database schemas through an intuitive sidebar interface.
- **Query History Tracking**: Review and revisit past queries for enhanced productivity and debugging.
- **AI-Driven Insights**: Leverages the `mistralai/devstral-small:free` model for reliable SQL query generation.
- **SQLite Database Upload**: Upload `.db` files to execute queries directly in the browser.

---

## 🛠️ Technology Stack

SequelFlow is built with modern, industry-standard technologies to ensure scalability, performance, and maintainability:

| Technology           | Purpose                              |
|----------------------|--------------------------------------|
| **Vite + React + TypeScript** | Fast, type-safe front-end development |
| **Tailwind CSS**     | Responsive, utility-first styling     |
| **OpenRouter API**   | AI-powered natural language to SQL    |
| **SQLite.js**        | In-browser SQL execution             |
| **MongoDB (Planned)**| Future support for storing DB metadata|

---

## 🚀 Getting Started

Follow these steps to set up and run SequelFlow locally:

### Prerequisites

- **Node.js**: Version ≥ 18.x
- **Package Manager**: NPM or Yarn
- **OpenRouter API Key**: Obtain from [OpenRouter](https://openrouter.ai/)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NITHINPOLI04/sequel-flow.git
   cd sequel-flow
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:
   Create a `.env` file in the project root:
   ```env
   VITE_OPENROUTER_API_KEY=your_api_key_here
   ```
   **Note**: Ensure the `.env` file is not committed to version control.

4. **Run the Application**:
   ```bash
   npm run dev
   ```
   Access the app at `http://localhost:5173` (or the port specified by Vite).

---

## 📂 Project Structure

```bash
├── public/                    # Static assets
├── src/
│   ├── components/            # Reusable UI components (e.g., Header, SchemaExplorer)
│   ├── services/              # API integrations (e.g., OpenRouter)
│   ├── App.tsx                # Core application logic
│   ├── main.tsx               # Application entry point
│   └── index.css              # Global styles with Tailwind CSS
├── .env                       # Environment variables (ignored by Git)
├── vite.config.ts             # Vite configuration
├── tailwind.config.js         # Tailwind CSS configuration
└── tsconfig.json              # TypeScript configuration
```

---

## 🔒 Security Practices

- **Environment Variables**: API keys are securely stored in `.env` and excluded from version control via `.gitignore`.
- **Input Sanitization**: User inputs are sanitized to prevent SQL injection or malicious queries.
- **Secure API Integration**: API keys are managed through environment variables for safe API calls.

---

## 🌱 Future Enhancements

- **MongoDB Integration**: Store uploaded database metadata for persistent access.
- **Advanced Query Optimization**: Enhance AI-generated SQL for performance and accuracy.
- **Expanded Database Support**: Add compatibility for PostgreSQL and MySQL.

---

## 📖 Why SequelFlow?

SequelFlow demonstrates expertise in modern web development, AI integration, and database management. It showcases proficiency in building scalable, secure, and user-centric applications with a focus on clean code, type safety, and responsive design. This project reflects a commitment to solving real-world problems with innovative technology.

---
