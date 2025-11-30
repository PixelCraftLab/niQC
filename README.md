# NeuroImaging Quality Control (niQC)

Welcome to the **niQC** repository! This project hosts the website for NeuroImaging Quality Control.

---

## Website Structure

The niQC website is built with **Gatsby**, a fast and modern static site generator. Every commit pushed to the `master` branch triggers a rebuild of the website and deployment to:

[https://incf.github.io/niQC/](https://incf.github.io/niQC/)

---

## Content Organization

All website content is stored in the `content` folder in **Markdown (`.md`) format**.

To create a new page:

1. Navigate to `content/pages`.
2. Create a new folder for your page.
3. Inside the folder, add an `index.md` file containing your page content.

### Example `index.md`:

```markdown
---
path: "/about"
title: "About"
menu: 4
---

# About!

Welcome to the About page!
