# Bibliography

The bibliography is a crutial part of any publications. Its usage in LaTeX documents in not hard but requires to properly understand the concept. This section is dedicated to summarize how to create and use a bibliography with concise and simple examples.

## Technologies

LaTeX Bibliography evolved a lot during the previous years. This section focuses on the latest technology available to easily reference any documents.

- **BibLaTeX**: Bib­li­o­graphic fa­cil­i­ties used to create a database of references.
- **Biber**: Tool used to transform the BibLaTeX database into a compiled file that LaTeX uses to bind the references into the document.

## Manage the database of references

Instead of maintaining the database of references by hand, it's recommended to use a software with a UI that can handle this tedious task.

For that purpose, the program called [JabRef](https://www.jabref.org/) is used. It natively supports BibLaTeX (despite this is a setting to enable in *File > Switch to BibLaTeX mode*).

In addition, if the program *TeXstudio* is used, the default bibliography tool must be set to *Biber*, under *Tools > Configure TexStudio > Build > Default Bibliography Tool*.

## Manage the reference keys

Each reference in the database is identified by a key (also called *BibtexKey*). Those keys are then used in the LaTeX document to cite a reference.

The structure of the key is up to the editor. Nonetheless, a good practice is to structure the keys as illustrated as follows. This convention is followed by Google Scholar as well.

> [last name of first author] [year] [first word of title]

As an example, Dr. Paul Ekwin has written a book called *What the face reveals: Basic and applied studies of spontaneous expression using the Facial Action Coding System (FACS)*, published in 1997.
To corresponding key for this book will be *ekman1997face*, where *ekman* is the last name of the first author, *1997* the date when the book has been published and *face* is the first *real* word on the title (let's ignore what, the, on, ...).

## Go further

In addition of the compendium, more information about the bibliography can be found on [ShareLaTeX](https://www.sharelatex.com/blog/2013/07/31/getting-started-with-biblatex.html) and a nice introduction for BibLaTeX on [BibLaTeX - Dickimaw-books](http://www.dickimaw-books.com/latex/thesis/html/biblatex.html).