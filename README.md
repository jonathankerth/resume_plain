# Jonathan Gallardo-Kerth · Resume

A minimalist, ATS-friendly HTML resume focused on readability for recruiting systems and hiring teams. The layout leans on semantic HTML and lightweight CSS—no frameworks, scripts, or hidden print tweaks.

## Live Resume

- **Resume (GitHub Pages):** https://jonathankerth.github.io/resume/
- **Direct PDF Download:** https://mypublicucket.s3.us-west-2.amazonaws.com/Jonathan+GK+Resume.pdf

## Tech Stack

- **HTML5** for accessible, semantic structure
- **CSS** (custom, no utility framework) for a clean black-and-white layout that looks identical on screen and in print

## Local Development

```bash
# Serve the static files with any dev server
git clone https://github.com/jonathankerth/resume.git resume-clean
cd resume-clean
python3 -m http.server 8080
# or use `npx serve .`
```

Open `http://localhost:8080` (or your chosen port) to preview. Edit `index.html` or `styles.css` directly for updates.

## Why This Version

- **ATS-first:** plain text hierarchy, consistent headings, and keyword-rich sections for parsing accuracy.
- **Human-friendly:** balanced whitespace, quick-scan contact row, and concise bullet points that highlight measurable impact.
- **One-page guarantee:** constrained content width keeps the output tidy for hiring managers without special print overrides.

Feel free to adapt this structure for your own resume—just make sure the content stays truthful and tailored to the roles you want.
