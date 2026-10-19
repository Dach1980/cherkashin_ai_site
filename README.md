# Dmitry Cherkashin — AI, Engineering & Education

A bilingual (Russian/English), responsive personal website and educational portfolio.

## Website sections

- **About:** engineering background, teaching, and practical AI approach.
- **Learning:** local AI and LM Studio, Python fundamentals, and Manus AI workflows.
- **Video courses:** YouTube playlists on local LLMs, LM Studio, and Manus AI.
- **Featured videos:** six direct previews using real YouTube thumbnails and links to the corresponding public videos.
- **Projects:** concise overviews of Project Expert AI, MCP Web Search, and Python Local RAG Course, including a visual PDF-to-expert-review workflow. Repository and individual MCP lesson links are intentionally not published on the website.
- **Collaboration and contact:** email and YouTube channel.

## Design and tech

- Inspired by the Manus concept: dark navy background, blue-violet gradients, luminous UI accents, and clear content cards.
- Plain HTML, CSS, and JavaScript; no build step or package installation.
- Responsive layout for desktop, tablet, and mobile, including compact video cards on phones.
- Real YouTube thumbnails are used for selected public videos; the hero illustration remains until a real portrait image is added to the site assets.
- RU/EN language switcher and reduced-motion accessibility support.
- External links open in a new tab with safe `rel` attributes.

## Run locally

Open `index.html` in a browser. For a local server, run from this directory:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Publish with GitHub Pages

This static site can be published without a build step. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save. GitHub will show the public URL when deployment is ready.

## Contact

dchpost@mail.ru
