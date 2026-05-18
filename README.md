# Edumynt Literature

**Deep dives into literary concepts, analysis, and educational content.**

Edumynt Literature is an open-source educational blog covering literary theory, book analysis, reading guides, and more. Built with [Astro](https://astro.build).

🌐 **Live site:** [literature.edumynt.in](https://literature.edumynt.in)

---

## 📖 About

This blog publishes accessible, well-structured articles on literature — from foundational concepts to advanced analysis. All content is free to read, share, and adapt under a copyleft license.

## 🤝 Contribute

We welcome contributions! You can help by:

### Writing Content
- Write new articles (EN or HI) on literature topics
- Follow the content guidelines in [`CONTRIBUTING.md`](./CONTRIBUTING.md)
- Submit a pull request with your article in `src/content/posts/`

### Suggest Edits
- Found a typo, outdated info, or have a suggestion?
- Click the **"Suggest Edit"** button on any article page
- Or [open an issue](https://github.com/Edumynt/edumynt-literature/issues/new?template=suggest-edit.md)

### Report Issues
- Broken links, rendering problems, or accessibility issues — [file a bug](https://github.com/Edumynt/edumynt-literature/issues/new?template=bug-report.md)

## 🛠️ Tech Stack

- [Astro](https://astro.build) — Static site generator
- [MDX](https://mdxjs.com/) — Markdown + JSX for interactive content
- [Tailwind CSS](https://tailwindcss.com/) — Styling
- [GitHub Pages](https://pages.github.com/) — Hosting
- [Cloudflare](https://www.cloudflare.com/) — DNS + CDN

## 🚀 Local Development

```bash
git clone https://github.com/Edumynt/edumynt-literature.git
cd edumynt-literature
bun install
bun run dev
# → http://localhost:4321
```

## 📁 Project Structure

```
edumynt-literature/
├── src/
│   ├── content/
│   │   └── posts/          # Blog posts (MDX)
│   │       ├── en/         # English posts
│   │       └── hi/         # Hindi posts
│   ├── layouts/            # Page layouts
│   ├── components/         # Reusable components
│   ├── pages/              # Route pages
│   └── config.ts           # Site configuration
├── public/                 # Static assets
├── .github/
│   ├── workflows/          # CI/CD
│   └── ISSUE_TEMPLATES/    # Issue templates
├── astro.config.mjs
└── package.json
```

## 📜 License

| Component | License |
|-----------|---------|
| **Code & Theme** | [GPL-3.0](LICENSE-GPL) |
| **Content & Articles** | [CC BY-SA 4.0](LICENSE-CC-BY-SA) |

See [LICENSE.md](LICENSE.md) for details.

## 🔗 Related Projects

- 🧠 [Edumynt Psychology](https://github.com/Edumynt/edumynt-psychology) — Psychology education
- ✍️ [Edumynt Grammar](https://github.com/Edumynt/edumynt-grammar) — English grammar guides
- 🌐 [Edumynt.in](https://edumynt.in) — Main landing page
- 📱 [Edumynt Blogs App](https://github.com/Edumynt/edumynt-blogs-app) — Mobile app (Android)

---

<p align="center">
  Built with ❤️ by <a href="https://edumynt.in">Edumynt</a> · <a href="https://github.com/Edumynt/edumynt-literature">GitHub</a> · <a href="https://literature.edumynt.in">literature.edumynt.in</a>
</p>
