# React2Next ⚡

> Instantly migrate React apps to Next.js.

React2Next is an open-source CLI tool that helps developers convert existing React applications into modern Next.js projects with minimal effort.

The goal of this project is to automate the migration process by analyzing React project structure and transforming it into a Next.js-compatible architecture.

---

## 🚀 Features

* Convert React Router to Next.js routing
* Generate Next.js App Router structure
* Convert `<img>` tags to `next/image`
* Detect React pages and migrate them automatically
* CLI-based migration tool
* AI-assisted migration (planned)

---

## 📦 Installation

You can run React2Next directly using **npx**:

```bash
npx react2next migrate ./my-react-app
```

Or install globally:

```bash
npm install -g react2next
```

Then run:

```bash
react2next migrate ./my-react-app
```

---

## ⚙️ Usage

Basic usage:

```bash
react2next migrate <path-to-react-project>
```

Example:

```bash
react2next migrate ./react-app
```

React2Next will:

1. Scan the React project
2. Detect routing and pages
3. Generate a Next.js project structure
4. Transform compatible code automatically

---

## 🧠 How It Works

React2Next combines **static code analysis** and **codemods** to transform React projects.

The migration process includes:

1. **Project Scanner**

   * Reads project structure
   * Detects dependencies

2. **Code Analyzer**

   * Parses React code using AST

3. **Migration Planner**

   * Determines how files should map to Next.js

4. **Code Transformer**

   * Rewrites imports, routing, and components

5. **Project Generator**

   * Creates a Next.js compatible project

---

## 📂 Project Structure

```
react2next
│
├── cli
│   └── index.ts
│
├── core
│   ├── scanner
│   ├── analyzer
│   ├── transformer
│   └── generator
│
├── utils
│
├── tests
│
├── README.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

---

## 🛣 Roadmap

### Phase 1 (MVP)

* React Router → Next.js routing
* Project structure generation
* Basic CLI migration

### Phase 2

* Image conversion (`img → next/image`)
* Metadata migration
* Environment variable migration

### Phase 3

* AI-assisted migration
* GitHub repository migration
* VSCode extension

---

## 🤝 Contributing

We welcome contributions from the community.

### How to Contribute

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/my-feature
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add: new migration feature"
```

5. Push your branch

```bash
git push origin feature/my-feature
```

6. Create a Pull Request

---

### Contribution Guidelines

* Follow the existing code structure
* Write clear commit messages
* Add tests when possible
* Ensure code builds successfully

---

## 🐞 Reporting Issues

If you find a bug or want to request a feature:

1. Go to **Issues**
2. Click **New Issue**
3. Provide clear details and reproduction steps

---

## 💡 Good First Issues

If you're new to the project, look for issues labeled:

```
good-first-issue
help-wanted
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Support the Project

If you find this project useful:

* Star the repository
* Share it with other developers
* Contribute to the project

---

## 👨‍💻 Author

**Amit Kumar**

Senior Frontend Engineer
React | Next.js | Web Architecture

GitHub: https://github.com/ellipticamit92
