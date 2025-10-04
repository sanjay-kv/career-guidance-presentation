# career-guidance-presentation
career-guidance-presentation

## Preview (Method 2) — Local HTTP server (recommended)

Use a lightweight HTTP server so the page behaves as it would when served over the web.

Option A: Python (if installed)

```powershell
cd 'd:\recode-hive-github\career-guidance-presentation'
python -m http.server 8000
# Open http://localhost:8000 in your browser
```

Option B: Node `http-server` (no install required via npx)

```powershell
cd 'd:\recode-hive-github\career-guidance-presentation'
npx http-server -p 8000
# Or, if you installed it globally:
# http-server -p 8000
# Open http://localhost:8000 in your browser
```

Stop the server with Ctrl+C in the PowerShell window.

Troubleshooting:
- If `python` or `npx` isn't found, install Python or Node.js and ensure they're in your PATH.
- If port 8000 is in use, change to another port, e.g. 8001.
- Use an incognito window or clear cache if changes don't appear.
