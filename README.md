# Vue 3 Shopping List

A tiny Vue 3 (Composition API) demo.

## ✨ Features

- Add items to the current list (Enter key supported)
- Remove single items or clear the whole list
- **Save** the current list under a name (stored in `localStorage`)
- **Edit/Update** a saved list (load it, tweak items, click **Update**)
- **Delete** a saved list (with a confirmation modal)
- Modals close on outside click (`@click.self`) and have a11y-friendly structure

> Saved lists are keyed by **name** (not timestamps). Simple on purpose.

## 🧱 Tech

- **Vue 3** (Composition API)
- Plain **HTML/CSS**
- **localStorage** for persistence

## 🚀 Quick Start

1. Clone/download.
2. Open `index.html` directly in a browser **or** run a quick server:
   ```bash
   # any of these is fine
   python3 -m http.server 8000
   # or
   npx http-server .
