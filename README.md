# 🌐 HTML Fundamentals

> **A structured, standards-compliant guide to modern HTML5 semantic markup, forms, accessible tables, multimedia embedding, and CSS layout.**

---

## 📌 Repository Overview

This repository demonstrates modern semantic HTML5 and CSS fundamentals through structured, accessible, and standards-compliant templates. It provides a foundational navigation hub in `index.html` connecting to dedicated topic pages with consistent navigation and shared styling in `css/style.css`.

---

## 🗂️ Project Structure

```text
html-fundamentals/
├── index.html                  # Central hub with navigation cards to all topic pages
├── css/
│   └── style.css               # Shared CSS styling (typography, cards, layout, responsive design)
├── pages/
│   ├── html-introduction.html  # Document structure (DOCTYPE, html, head, body, meta, headings)
│   ├── html-text-formatting.html # Semantic text tags (strong, em, mark, code, pre, sub, sup)
│   ├── links_images.html       # Hyperlinks, image optimization, alt attributes, anchor targets
│   ├── html-lists.html         # Ordered, unordered, and definition description lists
│   ├── html-tables.html        # Accessible tabular data with thead, tbody, tfoot, th, td
│   ├── html-forms.html         # Form controls, input validation, labels, fieldsets & buttons
│   ├── html-media.html         # Native HTML5 audio, video embedding & responsive media tags
│   └── semantic.html           # Semantic landmark layout (header, nav, main, article, section, footer)
└── assets/                     # Media asset directories (images, audio, video)
```

---

## 🔬 Topics & Standards Demonstrated

1. **Semantic HTML5 Landmarks**: Utilizing `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, and `<footer>` for search-engine accessibility and screen-reader hierarchy.
2. **Accessible Forms & Validation**: Implementing `<label for="...">`, pattern constraints, required indicators, and diverse HTML5 input types (`email`, `number`, `date`, `radio`, `checkbox`).
3. **Structured Tabular Data**: Clean table layouts with scope headers (`scope="col"`), `<caption>` tags, and column spanning (`colspan` / `rowspan`).
4. **Clean CSS Styling**: Shared styling in `css/style.css` establishing responsive flexbox/grid containers, typography scales, and clean button transitions.

---

## 🚀 Viewing the Project

Simply open `index.html` in any modern web browser:

```bash
# On Windows PowerShell
Start-Process index.html

# Or serve locally using Python
python -m http.server 8080
```

Then navigate to `http://localhost:8080` to explore all pages through the interactive hub.

---

## 📄 License

This repository is distributed under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Simran Gupta**
- GitHub: [@simnexis](https://github.com/simnexis)