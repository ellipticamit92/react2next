# Contributing to React2Next

Thank you for your interest in contributing to **React2Next**! 🎉

React2Next is an open-source project aimed at helping developers migrate React applications to Next.js automatically. Contributions from the community help improve the tool and make it more reliable for developers worldwide.

---

## Ways to Contribute

You can contribute in many ways:

* Fix bugs
* Implement new migration features
* Improve documentation
* Write tests
* Suggest new ideas
* Report issues

---

## Getting Started

### 1. Fork the Repository

Click the **Fork** button on GitHub and clone your fork locally.

```bash
git clone https://github.com/<your-username>/react2next.git
cd react2next
```

---

### 2. Install Dependencies

```bash
npm install
```

---

### 3. Run the Project

Run the CLI in development mode:

```bash
npm run dev migrate ./example-react-app
```

---

## Development Workflow

### Create a Branch

Create a feature branch before making changes.

```bash
git checkout -b feature/your-feature-name
```

Examples:

* `feature/router-migration`
* `fix/link-conversion`
* `docs/readme-update`

---

### Make Your Changes

Follow the existing project structure.

```
core/
  scanner/
  analyzer/
  transformer/
  generator/
```

Add new migration logic inside the **transformer** module.

---

### Commit Your Changes

Use clear and descriptive commit messages.

Examples:

```
Add: React Router migration support
Fix: Link conversion issue
Update: README documentation
```

---

### Push Your Changes

```bash
git push origin feature/your-feature-name
```

Then open a **Pull Request** on GitHub.

---

## Pull Request Guidelines

Before submitting a PR, please ensure:

* The code compiles successfully
* The CLI runs without errors
* Your changes follow the existing code structure
* You updated documentation if needed

PRs should include:

* Clear description of the change
* Reason for the change
* Any relevant examples

---

## Coding Guidelines

To keep the project consistent:

* Use **TypeScript**
* Follow simple and readable code practices
* Avoid unnecessary dependencies
* Keep functions modular

Example style:

```ts
function migrateRouter() {
  // transformation logic
}
```

---

## Project Architecture

React2Next follows a modular architecture.

```
react2next
│
├── cli          → CLI entry point
├── core
│   ├── scanner  → scans project structure
│   ├── analyzer → analyzes code using AST
│   ├── transformer → code migration logic
│   └── generator → generates Next.js structure
│
├── utils        → helper utilities
```

---

## Reporting Bugs

If you find a bug, please create a GitHub issue and include:

* Description of the issue
* Steps to reproduce
* Expected behavior
* Screenshots or logs (if available)

---

## Suggesting Features

Feature requests are welcome.

When suggesting a feature:

* Explain the problem it solves
* Provide example use cases
* Suggest possible implementation ideas

---

## Good First Issues

If you are new to the project, look for issues labeled:

* `good-first-issue`
* `help-wanted`

These are beginner-friendly tasks.

---

## Code of Conduct

Please be respectful and constructive when interacting with other contributors. We aim to create a welcoming and inclusive open-source community.

---

## Thank You ❤️

Your contributions help make **React2Next** better for developers everywhere.

If you like the project, consider:

* ⭐ Starring the repository
* Sharing it with other developers
* Contributing improvements
