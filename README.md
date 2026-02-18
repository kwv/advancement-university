# Advancement University

**Live site:** https://kwv.github.io/advancement-university/

BSA merit badge presentations built with [reveal.js](https://revealjs.com), hosted on GitHub Pages.

## Badges

| Badge | Slides |
|-------|--------|
| 💻 Programming | `badges/programming/slides.md` |
| 🤖 Artificial Intelligence | `badges/ai/slides.md` |
| 🔐 Cybersecurity | `badges/cybersecurity/slides.md` |

## Structure

```
index.html                      ← Landing page
badges/
  programming/
    index.html                  ← Presentation shell (loads slides.md)
    slides.md                   ← Edit this to change slides
  ai/
    index.html
    slides.md
  cybersecurity/
    index.html
    slides.md
_assets/
  theme.css                     ← Shared BSA color theme
```

## Editing Slides

All slide content lives in each badge's `slides.md`. The HTML shells are just reveal.js boilerplate and rarely need to change.

### Slide separators

| Separator | Meaning |
|-----------|---------|
| `\n---\n` (blank line, three dashes, blank line) | New horizontal slide |
| `\n--\n` | New vertical slide (sub-slide) |
| `Note:` | Speaker notes (press `S` during presentation) |

### Example

```markdown
# Requirement 1 — Safety

---

## 1a — Digital Safety

- Watch the Personal Safety Awareness video
- Discuss with parent/guardian

Note:
This is a speaker note — only visible in presenter view.

--

## 1b — Physical Safety

- Repetitive stress injuries
- Eye strain prevention
```

## Running Locally

reveal.js requires a web server to load external markdown files (won't work with `file://`).

**Option 1 — Python:**
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

**Option 2 — Node:**
```bash
npx serve .
```

**Option 3 — VS Code:**
Install the "Live Server" extension and click "Go Live".

## Deployment

GitHub Actions automatically builds and deploys to GitHub Pages on push to `main`. See `.github/workflows/deploy.yml`.

The site will be live at: `https://<your-username>.github.io/<repo-name>/`
