# 1001 Albums You Must Hear Before You Die

A musical reference book edited by Robert Dimery. It presents a list of 1001
influential and important popular music albums released between the 1950s and
the 2010s.

The book was first released in the year 2005, and has several reissues. The
content is revised in the later editions: as new albums are added, some albums
listed in previous versions are removed, particularly in the 2000s and 2010s
sections.

While the list of albums compiled in the book is available online in multiple
web pages and several GitHub repositories, either the quality of the data is
not satisfactory, the list is not machine-readable, or the version of data is
not clear (edition of the book is not listed).

The aim of this project is to provide a machine-readable list with good data
quality, and with clearly indicated corresponding book edition.

## The list

This work is based on a GitHub gist started back in 2012 and further developed
in 2019 (see the commit history). This gist corresponds to the 2008 edition of
the book: it differs from the 2005 edition by 20 albums in the 2000s section.

The original list was proofread and many mistakes were corrected, including,
but not limited to:

* wrong or incomplete artist credits,
* wrong or incomplete album titles,
* swapped artist names and album titles,
* incorrect usage of the definite article in names and titles,
* typos, missing diacritics and encoding issues,
* incorrect punctuation.

The list was also converted to a tab-separated format. It works better with
data containing commas, which often appear both in artist credits and album
titles.

Finally, since the differences between 2005 and 2008 edition of the book are
known, a separate list corresponding to the 2005 edition was added.

## Future work

Cross-reference the list with MusicBrainz data. This will allow to:

* add release group MBIDs,
* correct more errors in the list,
* improve accuracy of release dates.
