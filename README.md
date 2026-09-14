# CUET Student Email Generator

A polished, fully client-side web application for generating CUET student email addresses (Undergraduate & Postgraduate).

## Features

- **Undergraduate mode**: Batch (00–99) + Department + sequential 3-digit ID → `u{batch}{dept}{id}@student.cuet.ac.bd`
- **Postgraduate mode**: Year + department short code + number → `{year}{mdept}{num}@student.cuet.ac.bd`
- Searchable department dropdown
- Live email pattern preview
- Editable results table with multi-select
- Copy to clipboard (selected or all)
- Download as CSV / JSON / XLSX
- Add / delete individual emails
- Filter / search
- Dark & Light mode
- Fully responsive
- localStorage persistence
- Keyboard shortcut: `Ctrl/Cmd + Enter` to generate

## How to run

Simply open `index.html` in any modern browser. No build step or server required.

Alternatively serve it:

```bash
npx serve .
# or
python -m http.server 3000
```

## Tech

- Tailwind CSS (CDN)
- SheetJS (XLSX) + FileSaver.js
- Vanilla JS (no framework dependencies)
- Inter font

All data stays in the browser.
