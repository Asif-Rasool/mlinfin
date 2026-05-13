# Rasool Document Template v1.0 Style Guide

## Overview

Rasool Document Template (RDT) is the formatting standard for FIN 4950 documents. It keeps submissions readable and consistent while using Calibri and SELU-appropriate affiliation language.

## Typography

Use Calibri throughout editable formats when the platform supports it. Body text is Calibri regular, 11 pt, justified, with no first-line indentation. Set body paragraphs to 1.26 line spacing with 8.5 pt after each paragraph. Control these settings through the Normal style.

Bold and italics may be used for emphasis. Hyperlinks, inline code, superscripts, and subscripts are allowed.

## Page Layout

Use US Letter paper, 8.5 x 11 inches. Set the top margin to 1 inch. Set the bottom, left, and right margins to 1.5 inches. Place page numbers in the footer, centered or in a standard footer position, about 1 inch from the bottom. Keep decorative material out of the margins.

Keep body text, figures, tables, captions, references, and appendices inside the margins. Avoid shrinking margins, font size, or spacing to fit extra material into a page-limited assignment.

## Title Block

Use this structure:

```text
Rasool Document Template v1.0
For Use in FIN 4950
Author Name
Southeastern Louisiana University
email@example.edu
```

Set the title in Calibri regular, 17 pt, centered, with 1.15 line spacing and no color accent. Author name, affiliation, and email lines use Calibri regular, 11 pt, centered. The affiliation line should read “Southeastern Louisiana University.” The email line may be omitted for anonymous submissions or when the instructor gives different instructions.

## Abstract

Place the abstract below the title block. Begin with “Abstract” in bold italics, followed by an em dash. Use 0.5-inch left and right indents, 11 pt Calibri, justified alignment, 1.26 line spacing, and 8.5 pt spacing after.

Abstracts are optional. Use them for longer assignments that need a brief summary. Short assignments usually do not need one unless the prompt requires it.

## Headings

Use numbered headings without color accents. Heading 1 is 11 pt bold, all caps, with 11 pt spacing before and 8.5 pt after. Heading 2 is 11 pt bold upright, sentence case, with 8.5 pt before and after. Heading 3 is 11 pt bold italic, sentence case, with 8.5 pt before and after.

Heading 4 is a run-in sidehead: 11 pt bold italic, followed by an em dash, continuing into body text. Avoid headings beyond Heading 3 unless the document is complex. Word and LaTeX can handle numbering through styles or commands; Google Docs and Pages may require manual numbering or careful style setup.

## Figures

Center figures inside the margins and reference each figure in the body text. Use a thin border if a white-background figure is hard to see.

Place figure captions below figures. Captions use Calibri 8.5 pt, 14 pt line spacing, and 1-inch left and right indents. Set the label, such as “Figure 1,” in bold italics, followed by an em dash. Keep captions on the same page as the figure whenever possible.

## Tables

Center tables and keep them inside the margins. Place table captions above tables. A simple rule helps: figures are captioned below, tables are captioned above. Table captions follow the same formatting as figure captions.

Use a clean LaTeX-style table format: no shaded header row, no vertical grid lines, and horizontal rules only at the top, below the header, and at the bottom. Left-align text in tables. Right-align or decimal-align numeric columns. Table text may be smaller than body text, often matching caption size. Move large tables to appendices if they interrupt the document. Use editable tables instead of screenshots.

## Quotes

Short quotes can remain inline with quotation marks and citations. Set quotes longer than three lines as block quotes with 0.5-inch left and right indents. Use brackets only to clarify replaced words. Prefer paraphrase when a quote adds length without adding value.

## Lists

Use bulleted lists for parallel items. Use numbered lists for sequence, priority, or steps. Lists should use a 0.5-inch left indent, with the bullet or number hanging by about 0.25 inch. Keep list items parallel.

## Code, Formulas, and Technical Notation

Use inline code for variable names, file names, commands, or functions. Separate longer code blocks from the body text. Format mathematical notation consistently. Define variables before using them repeatedly.

## Citations

Use APA-style in-text citations by default unless the assignment, journal, client, or instructor requires another style. Place citations close to the claims they support. Avoid putting one citation only at the end of a long paragraph when several claims need support.

Examples include `(Rasool, 2026)`, `Rasool and Smith (2026)`, `(Rasool, 2026a; Rasool, 2026b)`, and `Rasool et al. (2026)`. Footnotes may be used for supplemental clarification, but they should not replace the default citation method. Footnotes should use Calibri 8.5 pt with 1.26 line spacing.

## References

Use a dedicated References section. Include only works cited in the body. Alphabetize references by the first author’s last name. If numbered references are used, numbering should follow the alphabetized order. Order multiple works by the same author chronologically. Mark same-author, same-year works with letters such as 2026a and 2026b.

## Appendices

Place appendices after References. If there are multiple appendices, use a Heading 1 called “APPENDICES” and Heading 2 labels for each appendix. If there is only one appendix, use “Appendix: Descriptive title.”

Appendices are optional. Use them for raw data, long tables, model diagnostics, extended calculations, or extra figures. Do not put the main argument in an appendix. The body should summarize appendix content and refer readers to the relevant appendix.

## Platform-Specific Notes

Microsoft Word supports the included paragraph and character styles directly. Google Docs and Apple Pages can recreate the same settings manually, although heading numbering may differ and may require manual numbering. LaTeX users should compile with XeLaTeX or LuaLaTeX for the closest font match; the Overleaf package also includes a pdfLaTeX fallback so students can still compile if the wrong compiler is selected.
