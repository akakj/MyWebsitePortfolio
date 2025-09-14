# My Website Portfolio

A fast, responsive personal portfolio built with **React + Vite** and **Tailwind CSS**. The goal is to showcase projects, skills, and experience with a clean, lightweight UI and great performance.

> Tech stack: React, Vite, Tailwind CSS, ESLint.
> Deploy anywhere (GitHub Pages, Netlify, Vercel).

---

## ✨ Features

* ⚡️ Blazing-fast dev/build with Vite
* 📱 Fully responsive layout
* 🧩 Component-based structure for easy customization
* 🎯 SEO-friendly metadata
* 🧹 Linting and formatting (ESLint config included)

---

## 🗂️ Project Structure (overview)

```
MyWebsitePortfolio/
├─ public/               # Static assets (favicons, images, etc.)
├─ src/                  # App source (components, pages, styles)
├─ index.html            # Vite entry HTML
├─ package.json          # Scripts & dependencies
├─ postcss.config.js     # Tailwind/PostCSS config
├─ tailwind.config.js    # Tailwind theme/config
└─ vite.config.js        # Vite config
```

---

## 🧩 Tailwind Setup

Tailwind is already configured via `postcss.config.js` and `tailwind.config.js`. Use utility classes directly in your React components, e.g.

```jsx
export default function Hero() {
  return (
    <section className="min-h-[60vh] grid place-items-center text-center p-8">
      <h1 className="text-4xl md:text-6xl font-bold">Hi, I’m <span className="text-primary">Jack</span> 👋</h1>
      <p className="mt-4 text-muted-foreground max-w-2xl">I build clean, performant web experiences.</p>
    </section>
  );
}
```

## 🤝 Contributing

This is a personal portfolio, but feel free to open issues or PRs for suggestions and improvements.

---

## 📄 License

No license specified yet. If you want others to be able to use parts of this project, add a `LICENSE` file (MIT is a common choice for portfolios).

---

## 👤 Author

**Anna Kandyba (**[@akakj](https://github.com/akakj))

* **Portfolio:** *annakandyba.com*
* **LinkedIn:**  *[linkedin.com/in/anna-kandyba/](https://www.linkedin.com/in/anna-kandyba/)*

---

## 🙌 Acknowledgements

* Built with [Vite](https://vitejs.dev/), [React](https://react.dev/), and [Tailwind CSS](https://tailwindcss.com/).
