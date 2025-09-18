Perfect — if you plan to host **FocusBlock** with GitHub Pages, you’ll want a **Demo** section in your README with direct links to the live app.

Here’s the updated `README.md` formatted for GitHub, with a **Demo section** added:

---

# FocusBlock 🔖

**Turn Quizlet sets into focused study blocks.**
FocusBlock is a lightweight web app that converts Quizlet JSON into interactive flashcards for active recall and study.

---

## ✨ Features

* 🔗 **Quizlet Integration** — paste a Quizlet set URL and fetch its JSON.
* 📝 **Q/A Formatter** — convert raw Quizlet JSON into clean Q/A pairs.
* 📚 **History Tracking** — remembers your past URLs + raw JSON for quick reuse.
* 🔄 **Flashcard Viewer** — flip cards, cycle with mouse scroll, or use navigation buttons.
* ✅ **Answer Retention** — correct answers stay **green**, wrong answers stay **orange**, even when you revisit.
* ⭐ **Bookmarks** — mark important cards and filter to just the bookmarked ones.
* 📱 **Mobile Friendly** — responsive design for studying anywhere.

---

## 🌐 Demo

You can try FocusBlock live here (hosted with GitHub Pages):

👉 [**Live Demo – FocusBlock**](https://your-username.github.io/focusblock/)

* [**Index Page**](https://your-username.github.io/focusblock/index.html) (paste Quizlet URL, convert JSON, and open flashcards)
* [**Flashcards Page**](https://your-username.github.io/focusblock/flashcards.html) (interactive study session)

*(Replace `your-username` with your GitHub username once you push the repo.)*

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/focusblock.git
cd focusblock
```

### 2. Open in your browser

Since it’s a static HTML/JS app, you can run it by just opening the files in a browser:

* `index.html` → Paste Quizlet URL, convert JSON, and open flashcards.
* `flashcards.html` → Interactive flashcard study session.

*(Optional) Run a local server:*

```bash
python3 -m http.server 8080
```

then visit [http://localhost:8080](http://localhost:8080).

---

## 📷 Screenshots

*(Add screenshots of Index + Flashcard screens here.)*

---

## 🛠️ Tech Stack

* **HTML5**
* **Vanilla JavaScript**
* **LocalStorage** (history & bookmarks)
* **Responsive CSS**
