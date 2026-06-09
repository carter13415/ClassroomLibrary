# Classroom Library System

A web-based classroom library management app. Teachers can manage books, students, checkouts, and reservations. Students can browse, check out, and reserve books.

## Run Locally

```bash
node server.js
```

Then open http://localhost:8000 in your browser.

- **Teacher login**: Sign in with teacher credentials
- **Student login**: Sign in with class code + student credentials
- **Admin panel**: http://localhost:8000/admin.html (password: `library123`)

## Features

- Book management (add, edit, delete, ISBN lookup, barcode scan)
- Student management
- Checkout/return with 14-day due dates
- Reservation system (max 3 per student)
- Overdue tracking
- Activity history
- Admin panel for teacher accounts
- Print-friendly catalog
- Filterable student book browser
- LocalStorage data persistence (no database needed)

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to Settings → Pages
3. Select root folder and save
4. Your site is live at `https://<username>.github.io/<repo-name>`

No server needed on GitHub Pages — it serves static files directly.
