# eCH-0056

Repository allowing the management and versioning of the document 
eCH-0056: "Geoservices application profile"

## Current version

The current version is 3.0 available [here](https://www.ech.ch/fr/ech/ech-0056/3.0)

## Ongoing revision

- [German version](https://github.com/MediaComem/eCH-0056/blob/main/document_de.pdf)
- [French version](https://github.com/MediaComem/eCH-0056/blob/main/document_fr.pdf)
## Document generation (editors only)

In order to generate the document, first install ascidoctor and the asciidoctor-pdf plugin:

```bash
gem install asciidoctor
gem install asciidoctor-pdf --pre
```

Then, to generate the PDF document, run the following command:

- `asciidoctor-pdf -a pdf-theme=assets/theme_de.yml -a pdf-fontsdir=assets/fonts document_de.adoc` for the German version
- `asciidoctor-pdf -a pdf-theme=assets/theme_fr.yml -a pdf-fontsdir=assets/fonts document_fr.adoc` for the French version