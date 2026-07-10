# My Professional Experience

This repository contains my resume/CV generated with **Quarto**, enabling multiple output formats:
- 📄 **PDF**: Professional printable document
- 🌐 **Blog/HTML**: Interactive web version
- 📋 **Markdown**: Plain text format

## Project Structure

```
.
├── _quarto.yml          # Quarto configuration
├── index.qmd            # Homepage redirect to resume
├── resume.qmd           # Main resume content
├── about.qmd            # About me section
├── styles.css           # Custom styles
├── .github/workflows/   # Auto-deploy on push to main
└── docs/                # Generated output (HTML, PDF) for GitHub Pages
```

## How to Generate Documents

### Option 1: Automatic deployment (recommended)

Push changes to `main`. GitHub Actions runs `quarto render` and publishes the `docs/` folder automatically.

### Option 2: Local build

#### Prerequisites
```bash
# Install Quarto
# Download from: https://quarto.org/docs/getting-started/installation.html

# Install TinyTeX for PDF support (optional)
quarto install tinytex
```

#### Generate All Formats
```bash
quarto render
```

Then commit and push the updated `docs/` folder.

## Live Preview
```bash
quarto preview resume.qmd
```

## Connect

- **Google Scholar**: [AguZClcAAAAJ](https://scholar.google.com/citations?user=AguZClcAAAAJ&hl=es)
- **ORCID**: [0000-0001-9476-0665](https://orcid.org/0000-0001-9476-0665)
- **LinkedIn**: [Rodríguez Salguera](https://www.linkedin.com/in/rodr%C3%ADguez-salguera/?skipRedirect=true)
- **GitHub**: [@VHugo-85](https://github.com/VHugo-85)
- **iNaturalist**: [rodriguez-salguera](https://www.inaturalist.org/people/rodriguez-salguera)

---

**Author**: Víctor Hugo Rodríguez Salguera  
**Last Updated**: 2026-07-08
