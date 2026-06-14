# 🔐 Link Vault

> A personal bookmark manager that lives entirely in a single HTML file — no server, no login, no clutter.

**[Live Demo](https://yukkuyuktha.github.io/link-vault)** &nbsp;·&nbsp; Built with vanilla HTML, CSS & JavaScript

---

## 🌱 The Story Behind It

I had this habit — I leave 20+ browser tabs open at the end of every workday because I know I will need them again tomorrow. Closing them feels like losing them. Saving them in Notepad works, but it looks messy and is impossible to search.

I wanted something that felt like an actual dashboard for my links: organized by project or category, searchable, and easy to use without any friction. So I built Link Vault — a single HTML file I can open in any browser, that stores everything locally and stays organized exactly the way I want it.

---

## ✨ Features

| Feature | Description |
|---|---|
| **Custom Sections** | Create named sections (Work, Skills, Social, etc.) with a colour label |
| **Sidebar Navigation** | Persistent sidebar listing all sections with live link counts |
| **Pinned View** | Dedicated page that surfaces all pinned links in one place |
| **Pin Links** | Pin important links so they appear first in their section |
| **Tags** | Add comma-separated tags to links; click any tag to filter across sections |
| **Edit Links** | Update title, URL, section, or tags anytime |
| **Grid / List View** | Toggle between a card grid and a compact list layout |
| **Copy URL** | One-click copy to clipboard with toast confirmation |
| **Search** | Real-time search across titles, domains, and tags (⌘K shortcut) |
| **Export JSON** | Download a full vault backup as a dated  file |
| **Import JSON** | Restore a vault from a previously exported backup |
| **Import Bookmarks** | Import a browser-exported bookmarks HTML file into a new section |
| **Dark Theme** | Dark-only, intentional — easier on the eyes for heavy daily use |
| **No dependencies** | No Node.js, no build step, no backend — open and use |

---

## 🚀 Getting Started

### Option 1 — Use directly (offline)
1. Download 
2. Open it in any browser
3. Done — your data saves automatically in your browser's localStorage

### Option 2 — Use the live link
Visit **[yukkuyuktha.github.io/link-vault](https://yukkuyuktha.github.io/link-vault)** — no download needed.

> **Note:** Your links are stored only in your own browser. No one else can see them — not even me. Each person who opens this gets their own completely empty, private vault.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
|  /  | Focus search |
|  /  | Open Add Link modal |
|  | Close any open modal |

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | App structure and modals |
| CSS3 (Custom Properties) | Theming, dark mode, sidebar layout, grid system |
| Vanilla JavaScript (ES6+) | All app logic — no frameworks |
|  | Persistent client-side storage |
|  API | Reading uploaded files for import |
|  API | Parsing browser bookmarks HTML |
|  | Copy URL to clipboard |
| Blob + Object URL | Triggering JSON file download |
| Google Favicon API | Auto-fetching site icons at runtime |
| Tabler Icons (CDN) | UI icon set |
| Google Fonts (CDN) | DM Sans (body) + Instrument Serif (display) |

---

## 🧠 Design Decisions

**Single-file architecture** — The entire app is one  file. Portable, offline-capable, zero setup.

**Flat data model** — Links store  as a reference rather than being nested inside section objects. This keeps the data flat and makes filtering, searching, and exporting straightforward.

**Sidebar over pill tabs** — As sections grow, horizontal pill tabs overflow and become unusable. A sidebar scales to any number of sections cleanly and shows counts at a glance.

**Dark-only theme** — Intentional. Link Vault is a daily-use tool. A carefully tuned dark theme reduces eye strain and avoids the generic toggle complexity.

**localStorage** — All data stays local in the user's own browser. Nothing leaves the machine unless explicitly exported. No accounts, no servers, no privacy concerns.

---

## 📸 Screenshot

<img width="951" height="439" alt="Screenshot 2026-06-14 194221" src="https://github.com/user-attachments/assets/328ba836-d3c9-439f-863c-fbc893096bb6" />


---

## 📄 License

[MIT](LICENSE) — free to use, modify, and share.

---

*Built by [Yuktha Mangalpally](https://github.com/yukkuyuktha)*
