# docxToHTML

This python script with the help of `pypandoc` and `pytidylib` python libraries, helps convert documents in markdown, reStructuredText, textile, HTML, DocBook, LaTeX, MediaWiki markup, TWiki markup, OPML, Emacs Org-Mode, Txt2Tags, Microsoft Word docx, LibreOffice ODT, EPUB, or Haddock markup to HTML file.

## Pre-requisites

* [pandoc 1.17.0.3](http://pandoc.org/installing.html)
* pypandoc
* libtidy-dev
* [Python tidylib package ](https://pypi.python.org/pypi/pytidylib/)
* tidylib-dev
* Python 2

## Compiling

`python docToHtml.py inputfile_name outputfile_name`

For example:

`python docToHtml.py document.docx output.html`

## Output

The `output.html` will be created in the same folder as the `docToHtml.py`. If your input file is not in the same directory as your `docToHtml.py`, then make sure you provide the proper path to your input file. If there are any images in the input file, then those will be added into the `media` directory in the same directory as `docToHtml.py`.

## References

* [Pandoc](http://pandoc.org/index.html)
* [word2html](https://github.com/bradmontgomery/word2html)
* [Let's convert a word doc to HTML](https://bradmontgomery.net/blog/lets-convert-word-doc-html/)
