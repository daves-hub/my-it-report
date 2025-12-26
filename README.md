# my-it-report
My SIWES IT Report

## LaTeX Template

This repository contains a LaTeX template for creating a professional SIWES (Students Industrial Work Experience Scheme) IT report.

### Template Specifications

- **Page Size**: A4
- **Body Font Size**: 12pt
- **Font Family**: Times New Roman
- **Document Class**: report

### Prerequisites

To compile this LaTeX document, you need:
- A LaTeX distribution (e.g., TeX Live, MiKTeX, or MacTeX)
- Or use an online LaTeX editor like Overleaf

### Compilation

To compile the document to PDF:

```bash
pdflatex report.tex
pdflatex report.tex  # Run twice to generate table of contents
```

Or use latexmk for automated compilation:

```bash
latexmk -pdf report.tex
```

### Template Structure

The template includes:
- Title page with customizable fields
- Declaration page
- Abstract
- Acknowledgements
- Table of contents
- Introduction chapter
- Activities and Tasks chapter
- Skills Acquired chapter
- Challenges and Solutions chapter
- Conclusion and Recommendations chapter
- References section
- Appendices

### Customization

Edit the following sections in `report.tex`:
1. Title page: Update your name, matriculation number, department, institution, and company details
2. Main chapters: Replace placeholder text with your actual content
3. References: Add your references in the bibliography section

### Features

- Professional formatting with Times New Roman font
- 1.5 line spacing for readability
- Fancy headers and footers
- Hyperlinked table of contents
- Customizable chapter and section titles
- Ready-to-use structure for IT reports
