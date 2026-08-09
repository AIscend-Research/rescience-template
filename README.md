# ReScience C article template (Overleaf)

Upload this folder to Overleaf and set:

- **Main document:** `article.tex`
- **Compiler:** XeLaTeX (required — the class loads the bundled OTF/TTF fonts via `fontspec`)

## Files

| File | What it is |
|---|---|
| `article.tex` | Main file — just pulls in the pieces below |
| `content.tex` | **Write your paper here** |
| `metadata.tex` | Title, authors, affiliations, dates, DOIs, abstract — edit by hand |
| `header.tex` | Title block, margin notes, copyright statement |
| `bibliography.bib` | References |
| `rescience.cls` | Journal class file — don't edit |
| `roboto/`, `source-*/` | Bundled fonts used by the class |
| `COPYING` | License |
