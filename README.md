# Madinah Arabic — Interactive Exercises

Interactive HTML exercises for **Madinah Arabic Book 1** (Shaykh Dr. V. 'Abdur-Raheem), covering chapters 1–3.

## Contents

| Page | Content |
|---|---|
| `index.html` | Landing page with chapter cards |
| `chapter1_exercise.html` | Basic Nouns, هذا/هذه, ما هذا؟ |
| `chapter2_exercise.html` | Adjectives, Noun-Adjective Agreement |
| `chapter3_exercise.html` | Prepositions (في, على, من, إلى), أين Questions |

Each chapter has 4 levels: **Word Match**, **Fill the Blank**, **Translation**, **Sentence Builder**.

## Usage

Open any `.html` file directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

All files are self-contained — no build step, no server-side dependencies.

## Hosting

Since everything is static HTML+CSS+JS, you can deploy by dropping the `Arabia/` folder onto any static host:

- **GitHub Pages** — push to a repo, enable Pages in Settings
- **Netlify** — drag `Arabia/` folder onto https://app.netlify.com
- **Vercel** — `npx vercel /path/to/Arabia --deploy`
- **Cloudflare Pages** — connect your Git repo

## Background

The page background uses `background.avif` (102 KB). The path is relative, so it works out of the box on any static host.


Content was reconstructed from OCR fragments and the known curriculum — no extractable text was available from the scanned PDF.

## License

Free to use, modify, and share.
