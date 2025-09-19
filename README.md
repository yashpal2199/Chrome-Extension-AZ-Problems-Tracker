# 🔖 Chrome Extension – AZ Problem Tracker

**AZ Problem Tracker** is a lightweight Chrome Extension that allows users to bookmark and manage problems from [Maang.in](https://maang.in) directly in their browser. It helps you quickly add, view, and organize problems you’re working on without losing track of progress.

---

## 🚀 Features

- **One-click bookmarking** of [Maang.in](https://maang.in) problems directly from the problem page.
- **Organize and track** saved problems for easy access later.
- **Mark progress** – solved/unsolved state for each saved problem.
- **Clean, minimal UI** integrated seamlessly with the Maang site.

---

## 🛠️ Technologies Used

| Layer       | Description                                   |
|-------------|-----------------------------------------------|
| **Frontend** | HTML, CSS for the popup and options UI        |
| **Logic**    | JavaScript for adding, storing, and retrieving problems |
| **Storage**  | Chrome Extension Storage API for persistence  |
| **Integration** | Chrome Extensions API for context menus and content scripts |

---

## ⚙️ How It Works

1. **On Maang Problem Page** – Click the extension icon to instantly bookmark the problem.
2. **Storage** – Problem details are stored using the Chrome Extension Storage API.
3. **Management** – Access the popup or options page to view, update, or delete saved problems.
4. **Sync** – Data stays available across browser sessions.

---
