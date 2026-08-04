# Jonathan Gallardo-Kerth · Resume

A minimalist, ATS-friendly HTML resume focused on readability for recruiting systems and hiring teams. Semantic HTML, lightweight custom CSS, and JSON-LD structured data — no frameworks and no client-side JavaScript.

## Live Resume

- **Resume (GitHub Pages):** https://jonathankerth.github.io/resume_plain/
- **Direct PDF Download:** https://mypublicucket.s3.us-west-2.amazonaws.com/Jonathan+GK+Resume.pdf

## Tech Stack

- **HTML5** for accessible, semantic structure, plus **JSON-LD** (schema.org Person) so search engines and AI crawlers get clean structured data
- **CSS** (custom, no utility framework) for a clean black-and-white layout, with a print stylesheet tuned for letter-size PDF export

## Local Development

```bash
# Serve the static files with any dev server
git clone https://github.com/jonathankerth/resume_plain.git
cd resume_plain
python3 -m http.server 8080
# or use `npx serve .`
```

Open `http://localhost:8080` (or your chosen port) to preview. Edit `index.html` or `styles.css` directly for updates.

## Why This Version

- **ATS-first:** plain text hierarchy, standard section headings, and keyword-rich sections for parsing accuracy — no tables, icons, or text-in-images.
- **Human-friendly:** balanced whitespace, quick-scan contact row, and concise bullet points that highlight measurable impact.
- **One page:** constrained content width and print rules keep the exported PDF to a single letter-size page.

Feel free to adapt this structure for your own resume — just make sure the content stays truthful and tailored to the roles you want.
