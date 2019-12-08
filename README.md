# masterthesis

Written in LaTex using the class TOPtesi.

### Managing the bibliography database

Bibliography is managed by bibtex. The `references.bib` file is the bibliography database.

After adding a new reference, to compile the bib file use the following commands:

```
pdflatex master_thesis_giovanni_garifo
bibtex master_thesis_giovanni_garifo
pdflatex master_thesis_giovanni_garifo
pdflatex master_thesis_giovanni_garifo
```

### Convert tex to docx

```
pandoc source.tex -o destination.docx
```