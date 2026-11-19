# AbhiramOS — Daily Discipline, Coding & Internship Tracker

A clean, responsive full-stack daily tracking web application built for **Abhiram (KMIT Narayanaguda, B.Tech CSE-AIML, 2-1)**.

## Project Structure
```text
abhiram-tracker/
├── index.html          # Main HTML structure
├── css/
│   └── styles.css      # Custom animations & styling
├── js/
│   ├── store.js        # Persistence & default data model
│   └── app.js          # Full interactive frontend logic
├── server/
│   └── server.js       # Optional Node.js + Express JSON-DB backend
└── package.json        # Node dependencies
```

## Option 1: Deploy Free on GitHub Pages (Frontend Only — Recommended)
GitHub Pages hosts static sites (`HTML`, `CSS`, `JavaScript`) directly with automatic browser persistence (`localStorage`) and JSON backup export/import.

1. Create a new **Public** repository on GitHub (e.g., `abhiram-tracker`).
2. Extract `abhiram-tracker-repo.zip` and upload all files (`index.html`, `css/`, `js/`, `server/`, `package.json`, `README.md`) to the repository.
3. Open **Settings → Pages** in your GitHub repository.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
5. Your live site will be ready at `https://<your-username>.github.io/abhiram-tracker/`.

## Option 2: Run Full-Stack Locally (with Node.js + Express Backend)
1. Install Node.js (v18+).
2. Run:
   ```bash
   npm install
   npm start
   ```
3. Open `http://localhost:3000` in your browser.
