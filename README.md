# 🔗 MiniLink — URL Shortener

A simple and clean URL shortener built with **Flask** and **SQLite**. Paste a long URL, get a short one, track visits, and delete when done.

---

## ✨ Features

- 🔗 Shorten any long URL instantly
- 📊 Track visit count for each short link
- 🗑️ Delete short links
- 📋 View all shortened URLs in a clean table
- 🔄 Auto-refreshes visit count when you switch back to the tab
- 🚀 Ready to deploy on Railway

---

## 🛠️ Tech Stack

| Layer             | Technology               |
| ----------------- | ------------------------ |
| Backend           | Python, Flask            |
| Database          | SQLite                   |
| Frontend          | HTML, Tailwind CSS (CDN) |
| Production Server | Gunicorn                 |

---

## 📁 Project Structure

```
URL-Shortner/
├── app.py              # Flask routes and app logic
├── models.py           # SQLite database functions
├── requirements.txt    # Python dependencies
├── Procfile            # For Railway/Render deployment
├── .gitignore          # Files excluded from git
└── templates/
    └── index.html      # Main UI
```

---

## 🚀 Run Locally

**1. Clone the repo**

```bash
git clone https://github.com/YOUR_USERNAME/url-shortner.git
cd url-shortner
```

**2. Create and activate a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the app**

```bash
flask run
```

Visit `http://localhost:5000` in your browser.

---

## ☁️ Deploy on Railway

1. Push this repo to GitHub
2. Go to [railway.app](https://railway.app) and sign in with GitHub
3. Click **New Project → Deploy from GitHub repo**
4. Select this repo — Railway auto-detects Python and deploys ✅
5. Go to **Settings → Networking → Generate Domain** to get your public URL

---

## ⚙️ Environment Variables

| Variable | Default   | Description                          |
| -------- | --------- | ------------------------------------ |
| `PORT`   | `5000`    | Port the app runs on                 |
| `HOST`   | `0.0.0.0` | Host address                         |
| `DEBUG`  | `false`   | Enable debug mode (`true` / `false`) |

---

## 📝 License

This project is open source and free to use.
