# My First Node.js GitHub Action

This repository contains a simple GitHub Action built using Node.js.
The action demonstrates how to create and run a custom GitHub Action within a repository.

---

## 📦 Project Overview

This GitHub Action runs a Node.js script (`index.js`) that prints a message to the GitHub Actions log.

It is triggered automatically whenever code is pushed to the repository.

---

## ⚙️ How It Works

1. A push is made to the repository.
2. GitHub triggers the workflow defined in `.github/workflows/test-action.yml`.
3. The workflow checks out the repository.
4. The custom GitHub Action runs using Node.js.
5. The script `index.js` executes and prints a message.

---

## 📁 Project Structure

```
.
├── index.js
├── action.yml
├── package.json
├── package-lock.json
├── .gitignore
└── .github
    └── workflows
        └── test-action.yml
```

---

## 🚀 Running the Action

The action runs automatically when you push code to the repository.

Example workflow step:

```yaml
- name: Run My Action
  uses: ./
```

---

## 🧩 Technologies Used

* Node.js
* GitHub Actions
* npm

---

## 📜 License

This project is licensed under the ISC License.
