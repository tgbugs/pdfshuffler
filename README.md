Forked from https://sourceforge.net/projects/pdfshuffler/

# PDF-Shuffler 0.7

This is the latest release of PDF-Shuffler, a simple pyGTK utility to merge,
split and rearrange PDF documents. PDF-Shuffler lets also rotate and crop
individual pages of a pdf document.

PDF-Shuffler requires python-poppler and version 1.10 or newer of python-pypdf.

PDF-Shuffler is written in Python using PyGTK. It is released under the GNU GPL-3.

In order to install run:

 python setup.py install

as superuser.


## What's new in this version:

* Port to Gtk+3 (new dependency on gir1.2-poppler-0.18).


## Known issues:

* High memory consumption.

* No autoscrolling during navigation with the keyboard arrows.

## Development

You'll need this libraries installed in your system:

* `gobject-introspection`
* `gtk`
* `poppler`

It's recomended to use [virtualenv](https://virtualenv.pypa.io/en/stable/) or
[pipenv](https://pipenv.pypa.io/en/latest/) to manage a local environment for
this package, then you can do

    pip install -e .

to install and

    pdfshuffler

to run.
