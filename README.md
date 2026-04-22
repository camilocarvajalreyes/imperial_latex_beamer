# Modified Imperial College London LaTeX templates

This is a modified version of the [original Imperial College London LaTeX template](https://github.com/ImperialCollegeLondon/imperial_latex_templates). It keeps Imperial font and colours, but allows for easier usage and some beamer-like commands.

NB: this version only includes the beamer template.

## Usage

To compile the file (same as the original template):
```
xelatex template_presentation.tex
```

When compiling with references, also run
```
biber template_presentation
```
followed by 
```
xelatex template_presentation.tex
```
once again.


## What is different from the official template?

### Cover in title page

A cover image is included. This image can be modified in "Presentation information", line 61, by changing the file location.

Title and subtitles use a smaller font as a consequence.

### Table of contents

A table of contents can be included using the command `\TOC`. This includes a table with blue background and better spacing than the original command.

### Title only pages

A slide with a large single piece of text can be included using `\titleBluePage{}` or `\titleWhitePage{}`, where the desired text is included between brackets. This can be useful when introducing new sections.

### References

The template includes an example library.bib file, which can receive citations in bibtex format. Citations are be made via `\cite{}' or '\autocite{}' (citation between round brackets). A reference slide is included at the end.

### Math font

A math-suitable format for the math environment is included by default. The template includes an example slide where this is shown.


## Copyright

© Imperial College London, 2024. These templates, including logo and fonts, are 
for use of Imperial staff and students only for university business. All rights 
reserved to the copyright owners.
