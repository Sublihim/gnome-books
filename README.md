# GNOME Books

Google Summer of Code project for GNOME.

Books is application for listing, searching and reading eBooks.
More information on https://wiki.gnome.org/Outreach/SummerOfCode/2014/Projects/MartaMilakovic_GnomeBooks

Books will be implemented upon the application gnome-documents, and it is going to live in the same git repository. This would be a great solution regarding code duplication, because it would be possible to reuse relevant code blocks from gnome-documents and add extra features related to eBooks.

Using epub.js library for the reading mode.

The idea is to integrate Books with an existing online eBook store.

## 1. Installing GNOME Books

    $ ./autogen
    $ make
    $ sudo make install
    $ export LD_LIBRARY_PATH=`pwd`/src/lib/.libs:$LD_LIBRARY_PATH
    $ export GI_TYPELIB_PATH=`pwd`/src

## 2. Running GNOME Books

    $ gnome-books
