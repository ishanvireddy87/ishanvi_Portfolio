# Ishanvi Reddy | Personal Portfolio

> A responsive, animated developer portfolio showcasing my deep learning,
> LLM-agent and Python projects, built with plain HTML, CSS and JavaScript.

**🔗 [Live site]([YOUR-LIVE-LINK])** ·
**💼 [LinkedIn](https://www.linkedin.com/in/ishanvi-reddy-b39b30417/)** ·
**🐙 [GitHub](https://github.com/ishanvireddy87)**

---

## What this is

A single-page portfolio that presents my background, skills, projects,
hackathons and certifications in one place. Features:

1. **Animated hero.** Interactive neural-network canvas background and a
   typing effect cycling through my roles.
2. **Interactive projects.** Filter by category and open a details popup
   for each project.
3. **Polished experience.** Dark/light theme (remembered between visits),
   scroll animations, active-section navigation and a mobile menu.
4. **Accessible.** Respects the reduced-motion setting and works on phones,
   tablets and desktops.

---

## Stack

| Layer      | Tools                                          |
|------------|------------------------------------------------|
| Frontend   | HTML5, CSS3 (custom properties), vanilla JS    |
| Graphics   | HTML Canvas (neural-network animation)         |
| Deploy     | Render static site / GitHub Pages              |

No frameworks, no build step, no dependencies.

---

## Run locally

Requirements: any modern web browser.

```bash
# 1. Clone the repo
git clone https://github.com/ishanvireddy87/[REPO-NAME].git
cd [REPO-NAME]

# 2. Open the site
# Double-click index.html, or serve it locally:
python -m http.server 8000
```

Open http://localhost:8000.

---

## Deployment

**Render:** New + → Static Site → select this repo → Publish Directory `.`
(leave Build Command blank).

**GitHub Pages:** Settings → Pages → Deploy from branch → `main` → `/ (root)`.

Every commit to `main` redeploys automatically.

---

## Repository structure

```
.
├── index.html     # The entire site (HTML, CSS and JS)
├── render.yaml    # Render static-site config
└── README.md
```

---

## Customizing

- **Colors:** edit the CSS variables in the `:root` block at the top of `index.html`.
- **Hero roles:** edit the `roles` array in the script.
- **Projects:** copy a project `<article>` card and add a matching entry in the `data` object.

---

## Author

**Marri Ishanvi Reddy**: B.Tech, Artificial Intelligence & Data Science,
KL University, Hyderabad (Expected 2028)

GitHub: [ishanvireddy87](https://github.com/ishanvireddy87) ·
LinkedIn: [ishanvi-reddy](https://www.linkedin.com/in/ishanvi-reddy-b39b30417/) ·
Email: ishanvireddy87@gmail.com
