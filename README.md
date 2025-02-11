# Personal Portfolio

A personal portfolio website built with **HTML + CSS** (no build step),
showcasing biography, academic and professional information, resume details
and personal interests. Live at
[GitHub Pages](https://dani2044.github.io/Personal-web-page/).

## Pages

| Page | Content |
| ---- | ------- |
| **Home** (`index.html`) | Hero, intro, highlights (scholarship, internship, research interests). |
| **Biography** (`data.html`) | Profile card and biographic facts. |
| **Resume** (`cvs.html`) | Education, achievements, experience, skills, languages, references and contact. |
| **Interests** (`hobbies.html`) | Movies, books, games, sports, community and an IoT project video. |

## Design

- Static, dependency-free, mobile-responsive layout.
- Dark theme with a blue→indigo accent gradient, custom CSS variables and
  smooth hover transitions.
- Typography via Google Fonts (**Inter** + **Sora**).
- Consistent sticky header and footer across pages.

```
.
├── index.html          # root meta-redirect to html/
├── html/               # the four site pages
├── css/                # design system + per-page styles
└── images/             # photos and icons
```

## Running locally

Open any page directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# open http://localhost:8000/html/
```

## License

[MIT](LICENSE) — see the license file for details.