# 📘 Markdown Template Repo

This repository provides a clean and opinionated setup for writing high-quality `README.md` files and
other markdown documents. It's built to help you (and your team/students) write **clean**, **consistent**,
and **error-free** documentation using:

- ✅ Prettier (formatting)
- ✅ markdownlint (style linting)
- ✅ cspell (spell checking)
- ✅ ls-lint (file and folder naming consistency)

---

## ✨ Features

- Enforces **markdown style rules** (headings, lists, spacing, etc.)
- Automatically formats markdown files on command
- Detects **spelling errors** using an extendable dictionary
- Checks for **consistent kebab-case naming** in files/folders
- All tools run via `npm` scripts (no need to remember commands)

---

## 🧰 Requirements

- [Node.js](https://nodejs.org/) (version 14 or higher recommended)
- npm (comes with Node.js)

---

## 🚀 Getting Started

1. **Clone the repo**:

   ```bash
   git clone https://github.com/your-username/markdown-template.git
   cd markdown-template
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Start writing your Markdown files** (e.g., `README.md`, `week-1.md`, `notes/lesson.md`)

---

## 🛠️ Available Commands

| Script                 | Description                                         |
| ---------------------- | --------------------------------------------------- |
| `npm run format`       | Format all markdown files using Prettier            |
| `npm run format:check` | Check for formatting issues without modifying files |
| `npm run spell-check`  | Run spell check on all files using `cspell`         |
| `npm run lint:md`      | Lint markdown files for style using `markdownlint`  |
| `npm run lint:ls`      | Lint filenames and folder names using `ls-lint`     |

---

## 📁 Recommended Project Structure

```bash
markdown-template/
├── README.md
├── week-1.md
├── notes/
│   └── introduction-to-html.md
├── .prettierrc
├── .cspell.json
├── .ls-lint.yml
├── .markdownlint.jsonc
├── package.json
```

---

## 📄 Configuration Files

### ✅ `.prettierrc`

Defines markdown formatting rules like indentation, quotes, line width, etc.

### ✅ `.markdownlint.jsonc`

Enforces markdown best practices: heading levels, line length, bullet style, etc.

### ✅ `.cspell.json`

Spell check config with custom dictionaries and ignored words.

### ✅ `.ls-lint.yml`

Enforces consistent **kebab-case** naming for files and directories.

---

## ✅ Best Practices

- Use `npm run format` before committing your markdown files
- Run `npm run lint:md` and `npm run spell-check` to avoid errors
- Stick to **kebab-case** for file/folder names (`week-1.md`, not `Week1.md`)
- Keep headings structured (e.g., no skipping from H1 → H4)

---
