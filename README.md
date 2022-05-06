---
output:
  html_document: default
  word_document: default
---
## Preface of the Project
-  This project showcases how to Automate the Report Generation using `Rmarkdown` and `Latex`.
- Project requires you to have basic knowledge of Markdown language as well as R and Latex.
- `Latex` is the language which is used to `generate report` or `Write a research paper`
- General Heiarchy of the default Latex document is :
  1. Preamble
  2. Main Document
  3. End Document
  
```{=latex}
\begin{tabular}{|p{4cm}|p{6cm}|}
\hline
  Farm ID & {`r in.filename`} \\[6pt]
\hline
  Farmer & Ralla Vagu  \\[6pt]
\hline
  Date of Testing & {`r date`} \\[6pt]
\hline
  Location & Kalakota \\[6pt]
\hline
```
