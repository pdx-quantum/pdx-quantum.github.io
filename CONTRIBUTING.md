How to contribute
=================

To contribute a paper summary, all you need to do is place a markdown file in
one of the directories contained in `_bibentries` in the project root. The
contents of the file should look like this, at a minimum:

```
---
author: John Smith, Bob Jones, Grant Steel and Albert Pimkin
title: "A Paper: Words Written on Several Pages"
year: 1984
howpublished: Some Journal, volume 12, number 3
abbrev: SJS84
---

<summary>
```

The part at the top between the `---`s is called the frontmatter. The fields
above are mandatory, since they're used generate a bibtex reference. If
possible, please also include in the frontmatter a URL where the PDF can be
found (not behind a paywall) or the URL of the paper's Arxiv page. These should
have the keys `pdf` or `arxiv`, respectively. Note that URLs or anything else
containing a `:` in the frontmatter must be quoted (see the `title` field above.

The possible frontmatter keys are
* `author` The authors in the order they appear in the paper. No Oxford comma.
  *(required)*
* `title` The title of the paper. *(required)*
* `year` The year the paper was published. *(required)*
* `howpublished` The conference, journal, or website where the paper was
  published. Specify the volume, number, pages, etc. as appropriate without
  abbreviating. *(required)*
* `abbrev` An abbreviation for the paper. If the paper has just one author, use
  the first three letters of their last name, followed by the last two digits
  of the publication year. If the paper has more than one author, use their last
  initials in the order in which they appear in the paper, up to the first
  three. E.g., a paper by John Smith published in 2015 would have the
  abbreviation `Smi15`, whereas a paper with two authors might have `SJ15`. If
  the resulting abbreviation isn't unique, add letters from each author's last
  name until it is, e.g. `SmJo15`. *(required)*
* `pdf` URL of a (freely available) copy of the PDF in quotes.
* `arxiv` URL of the paper's Arxiv page in quotes.

By way of convention, please name the file the same as the `abbrev` field plus
the `.md` extension.
