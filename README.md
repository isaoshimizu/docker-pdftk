# Docker image for PDFtk

This repository is unofficial.
PDFtk is a simple tool for doing everyday things with PDF documents.

Official site
https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/

## How to use Docker image

Extract the third page of a given PDF file.

```
docker run -it -v $(PWD):/mnt isaoshimizu/pdftk /usr/bin/pdftk /mnt/input.pdf cat 3 output /mnt/output.pdf
```
