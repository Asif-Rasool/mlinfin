# RDT Overleaf Guide

## Quick Start

Use the Overleaf package file `RDT_Overleaf.zip`.

1. Go to Overleaf.
2. Select **New Project**.
3. Choose **Upload Project**.
4. Upload `RDT_Overleaf.zip`.
5. Open the project.
6. In **Menu**, confirm that **Compiler** is set to **XeLaTeX** for the closest match to the Word template.
7. Open `rdt_latex_template.tex`.
8. Replace the placeholder title block, abstract, headings, body text, tables, figures, references, and appendix text.
9. Click **Recompile**.
10. Download the PDF when finished.

## Title Block

Keep the FIN 4950 course line in the title block:

```text
Rasool Document Template v1.0
For Use in FIN 4950
Author Name
Southeastern Louisiana University
email@example.edu
```

Edit the author name and email address. Keep the affiliation line as “Southeastern Louisiana University” for this class template unless the instructor gives different instructions.

## Compiler Choice

RDT uses `fontspec` with XeLaTeX or LuaLaTeX so the template can use Calibri when Calibri is available. Overleaf may not provide Calibri by default, so the template falls back to Carlito, a compatible open font. XeLaTeX gives the closest match to the Word version.

The template also includes a pdfLaTeX fallback so a project can still compile if Overleaf uses the wrong compiler. In fallback mode, the output uses a Helvetica-like sans serif font instead of Calibri or Carlito.

## What Students Edit

In `rdt_latex_template.tex`, update:

- The author name and email address.
- The abstract, if the assignment needs one.
- The numbered sections and subsections.
- Figure placeholders and captions.
- Table content and captions.
- In-text citations.
- The numbered reference list.
- Appendices, if needed.

## Formatting Already Built In

The LaTeX template sets US Letter paper, 1-inch top margin, 1.5-inch bottom/left/right margins, 11 pt body text, 1.26 line spacing, 8.5 pt paragraph spacing, centered 17 pt title block, RDT heading styles, captions, tables, block quotes, lists, references, and appendix behavior.

## Common Issues

If the project shows a `fontspec` error, open **Menu**, set **Compiler** to **XeLaTeX**, click **Clear cached files** from the logs panel if needed, then recompile. The included `latexmkrc` file also tells Overleaf to use XeLaTeX for this project.

If the font looks slightly different from the Word template, Overleaf is probably using Carlito or the pdfLaTeX fallback. The layout and spacing rules remain the same.

If heading numbering does not match the assignment structure, edit the section commands directly. Use `\section`, `\subsection`, and `\subsubsection` for the main hierarchy.
