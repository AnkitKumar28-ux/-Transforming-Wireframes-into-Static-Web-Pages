# NovaFlow — Wireframe to Static Web Page (HTML5 & CSS3)

This folder contains all deliverables for the **Wireframe to Responsive Static Web Page** task.

## Included Files in This Folder

1. **`index.html`** — Complete semantic HTML5 static web page replicating the wireframe structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`) with an interactive **Wireframe Blueprint Toggle**.
2. **`styles.css`** — Complete CSS3 stylesheet using CSS Custom Properties (design tokens), CSS Grid, Flexbox, fluid typography (`clamp()`), and responsive media queries (`1024px`, `768px`, `480px`).
3. **`REPORT.md`** — Detailed Markdown project report explaining wireframe analysis, semantic HTML choices, CSS layout strategies, responsiveness, and problem-solving solutions.
4. **`REPORT.pdf`** — Printable PDF version of the project report.
5. **`server.js`** — Zero-dependency Node.js HTTP server to run the webpage on `http://localhost:8000`.
6. **`server.ps1`** — Zero-dependency PowerShell HTTP server fallback for `http://localhost:8000`.
7. **`run-localhost.bat`** — One-click Windows launcher that starts the local server and opens `http://localhost:8000` in your browser.
8. **`wireframe-to-webpage.zip`** — Complete ZIP archive of all project files for easy submission.

## How to Run on Localhost

### Option 1: Double-Click Launcher (Windows)
Double-click **`run-localhost.bat`** in this folder. It will automatically start the local server and open **`http://localhost:8000`**.

### Option 2: Terminal (Node.js)
```powershell
cd C:\Users\pc\.gemini\antigravity\scratch\wireframe-to-webpage
node server.js
```
Then visit **`http://localhost:8000`** in your browser.
