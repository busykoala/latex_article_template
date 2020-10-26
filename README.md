# Handout Example

A latex template for an article using `ieee` citation style.

## How this stuff is setup

The file `handout.tex` is the main file to work with. It contains the document
class `article` followed by the package includes, header/footer setup and the
settings for the date.

In the `document` part there are examples for citing, references within the
document, a figure, a table, an equation and then all the tables (figures,
tables and bibliography).

Currently the document is set to German. It can be set to English easily in the
header part (`ngerman` -> `english`).

### Bibliography

The bibliography is pulled from the `bib/literature.bib` file which can be
extended with more entries and used by the keywords (try to get them from e.g.
books.google.com (search & select book -> on the left press `about this book`
-> scroll to bottom -> Export: BiBTeX -> copy entry from downloaded file)).

## Compile document

```
pdflatex handout
bibtex handout
pdflatex handout
pdflatex handout
```
