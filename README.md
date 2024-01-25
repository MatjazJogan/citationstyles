# Citation Styles, LaTeX Commands, and Examples

This document provides an overview of various citation styles, their typical use in scientific fields, LaTeX commands for implementing them, and examples of how citations appear within the text and in the bibliography.

## 1. APA (American Psychological Association)

- **Field:** Psychology, Education, and other Social Sciences
- **LaTeX Package:** `\usepackage{apacite}`
- **In-text Citation Example:** (Smith, 2020)
- **Bibliography Entry Example:** Smith, J. (2020). *Title of the work*. Publisher.

## 2. MLA (Modern Language Association)

- **Field:** Humanities, especially Literature and Language studies
- **LaTeX Package:** `\usepackage[style=mla]{biblatex}`
- **In-text Citation Example:** (Smith 45)
- **Bibliography Entry Example:** Smith, John. *Title of the Work*. Publisher, 2020.

## 3. IEEE (Institute of Electrical and Electronics Engineers)

- **Field:** Engineering, Computer Science, and Information Technology
- **LaTeX Package:** `\usepackage{cite}` and `\bibliographystyle{IEEEtran}`
- **In-text Citation Example:** [1]
- **Bibliography Entry Example:** [1] J. Smith, "Title of the paper," in *Name of the Journal*, vol. 10, no. 2, pp. 100-110, 2020.

## 4. Chicago Manual of Style

- **Field:** Broad range, including History, Arts, and Humanities
- **LaTeX Package:** `\usepackage[notes,backend=biber]{biblatex-chicago}` or `\usepackage[authordate,backend=biber]{biblatex-chicago}`
- **In-text Citation Example:** (Smith 2020, 100-110)
- **Bibliography Entry Example:** Smith, John. 2020. *Title of the Work*. Publisher.

## 5. Nature Style

- **Field:** Sciences, particularly Natural and Physical Sciences
- **LaTeX Package:** Custom `biblatex` style or manual formatting
- **In-text Citation Example:** (1)
- **Bibliography Entry Example:** 1. Smith, J. Title of the article. *Name of the Journal* **10**, 100-110 (2020).

## 6. Vancouver

- **Field:** Medicine and Health Sciences
- **LaTeX Package:** `\usepackage[style=vancouver]{biblatex}`
- **In-text Citation Example:** [1]
- **Bibliography Entry Example:** 1. Smith J. Title of the article. *Name of the Journal*. 2020;10(2):100-110.

## 7. Harvard

- **Field:** Various, including Business, Education, and Social Sciences
- **LaTeX Package:** `\usepackage{natbib}` or `\usepackage[style=authoryear]{biblatex}`
- **In-text Citation Example:** (Smith, 2020)
- **Bibliography Entry Example:** Smith, J. (2020). *Title of the Work*. Publisher.

## 8. ACS (American Chemical Society)

- **Field:** Chemistry
- **LaTeX Package:** `\usepackage{achemso}`
- **In-text Citation Example:** (1)
- **Bibliography Entry Example:** 1. Smith, J. Title of the Article. *Name of the Journal* **2020**, 10 (2), 100-110.

## 9. AMA (American Medical Association)

- **Field:** Medicine and Health Sciences
- **LaTeX Package:** Custom `biblatex` style or manual formatting
- **In-text Citation Example:** (1)
- **Bibliography Entry Example:** 1. Smith J. Title of the article. *Name of the Journal*. 2020;10(2):100-110.

## 10. OSCOLA (Oxford Standard for the Citation of Legal Authorities)

- **Field:** Law
- **LaTeX Package:** `\usepackage{oscola}`
- **In-text Citation Example:** (Smith 2020)
- **Bibliography Entry Example:** Smith, John, *Title of the Work* (Publisher 2020).

