# Awesome Scientific Writing [![Awesome][awesome-badge]](https://github.com/sindresorhus/awesome)

> Scientific writing can extend beyond LaTeX, made possible by formats,
> such as
> [Markdown](https://commonmark.org/) (and its many flavours),
> [reStructuredText](http://docutils.sourceforge.net/docs/ref/rst/directives.html) and
> [Jupyter notebooks](https://jupyter.readthedocs.io/en/latest/).

:star: means **really _awesome/useful_**.<br />
:bookmark: means ability to **seamlessly cite references**.<br/>
:link: means ability to **cross-reference figures and sections within the
document**.<br/>
**Σ** means ability to **write equations in LaTeX**.<br/>

## Contents
* [Bibliography](#bibliography)
- [Converters](#converters)
- [Demos](#demos)
    - [Articles](#articles)
    - [Presentations](#presentations)
- [Resources](#resources)
- [Other Awesome Lists](#other-awesome-lists)

### Bibliography
> Bibliography managers to generate citations / BibTeX / BibLaTeX files.

* [Zotero](https://www.zotero.org/): FOSS tool to collect, organize, cite, and
  share research.


### Converters
> Converters which can generate LaTeX, HTML or PDF output on demand.

- [academicmarkdown](https://github.com/smathot/academicmarkdown#readme): A
    Python wrapper over Pandoc with specialized extensions to parse certain
    elements, making it a superset of Pandoc markdown flavour :bookmark:
    :link: **Σ**.
- [bookbook](https://github.com/takluyver/bookbook/#readme): An experimental Python
    package which extends `nbconvert` and adds the ability to cross reference
    within and across notebooks :link: **Σ**.
- [bookdown](https://github.com/rstudio/bookdown/#readme): R package to facilitate
    writing books and long-form articles/reports with R Markdown :star:
    :bookmark: :link: **Σ**.
- [docutils](http://docutils.sourceforge.net/docs/): Python package which can
    convert reStructuredText into various formats and provides command-line
    tools to do it :link: **Σ**.
- [ipypublish](https://github.com/chrisjsewell/ipypublish/#readme): A workflow for
    creating and editing publication ready scientific reports and presentations,
    from one or more Jupyter Notebooks, without leaving the browser! :bookmark:
    :link: **Σ**.
- [nbconvert](https://nbconvert.readthedocs.io/en/latest/) - Convert Jupyter
    notebooks into `reveal.js` presentations, PDF, HTML, Markdown,
    reStructuredText and more **Σ**.
- [org-mode](https://orgmode.org) - Powerful Emacs package for authoring notes,
    TODO lists, spreadsheets, documents, executable code-blocks and a lot more
    in a plain text format called Org :star: :bookmark: :link: **Σ**.
- [pandoc](https://pandoc.org/MANUAL): A Haskell library for converting from
    one markup format to another, and a command-line tool that uses this
    library :star: :bookmark: :link: **Σ**.
- [scholdoc](http://scholdoc.scholarlymarkdown.com/): A fork of Pandoc and the
    reference implementation for ScholarlyMarkdown, a superset of Pandoc
    Markdown flavour :bookmark: :link: **Σ**.

### Demos
> Demos can include working examples, tutorials, videos demonstrating how to
> generate articles and presentations for scientific purposes.

#### Articles
- [bookdown-demo](https://github.com/rstudio/bookdown-demo/#readme) - Minimal
    example of a book based on R Markdown and bookdown.
- [Book on Riemann solvers](https://github.com/clawpack/riemann_book/#readme) - This
    example uses a custom `nbconvert` template and shows how to store your
    notebooks with no output (for version control) while automatically executing
    them before running `bookbook`, so that PDF and HTML versions include the
    output.
- [Katrin Leinweber's Ph.D.
    thesis](https://github.com/katrinleinweber/PhD-thesis/#readme) - Automated
    work flow involving several tools, but primarily Pandoc, `latexmk` and
    AcademicMarkdown.
- [Pandoc Markdown-Latex Boilerplate
    ](https://github.com/davecap/markdown-latex-boilerplate/#readme) -
    Demonstrate how to integrate Pandoc with an existing LaTeX template which
    requires some boilerplate code (i.e. LaTeX preamble), thus avoiding the
    `latexmk` dependency.
- [scientific-markdown](https://github.com/JensErat/scientific-markdown/#readme) -
    An example for use of Markdown for scientific publications using Pandoc and
    `latexmk` :star:.
- [Template for writing a PhD thesis in
  Markdown](https://github.com/tompollard/phd_thesis_markdown#readme) - A clean
    organization of files to provide a framework for writing a PhD thesis in
    mostly Markdown with a little bit of LaTeX, and compiled with Pandoc.
- [Writing scientific papers for ACPD using Emacs Org-mode
    ](https://www.draketo.de/english/emacs/writing-papers-in-org-mode-acpd) -
    Detailed tutorial on authoring a paper by seamlessly integrating with LaTeX
    commands within Org-mode.
- [Writing a  Book With Vim, Restructured Text, and
    Sphinx](https://www.tompurl.com/2012-11-22-writing-a-book-with-vim.html) - A
    blog post describing the work flow for writing a book with
    reStructuredText.

#### Presentations
- [pandoc-starter](https://github.com/jez/pandoc-starter/#readme) - Templates for
    articles, beamer presentations etc. using Markdown files and Makefiles for
    getting started with Pandoc.
- [slides](https://github.com/cgroll/slides/#readme) - Demo for generating `reveal.js`
    presentations using Pandoc.

### Extras
> Supplementary files and tools.

* [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) -
  Enhanced exporting tool for Zotero.
- [Citation Style Language (CSL) styles](https://editor.citationstyles.org/) -  A
  crowdsourced repository with over 9000 free CSL citation styles and an online
  editor to create new ones.
- [fzf-bibtex](https://github.com/msprev/fzf-bibtex/#readme) - A BibTeX source
  with vim integration which uses fzf (a fuzzy finder implemented in Go).
* [Panflute](http://scorreia.com/software/panflute/) - A pythonic alternative
  to John MacFarlane’s pandocfilters.
* [vim-pandoc](https://github.com/vim-pandoc/vim-pandoc/#readme) - 
  Pandoc integration and utilities for vim
* [vim-pandoc-syntax](https://github.com/vim-pandoc/vim-pandoc-syntax/#readme) -
  Lightweight rendering of pandoc syntax in Vim.

### Other Awesome Lists
- [Jupyter](https://github.com/markusschanta/awesome-jupyter/#renderingpublishingconversion)
- [LaTeX](https://github.com/egeerardyn/awesome-LaTeX/#readme)
- [Markdown](https://github.com/BubuAnabelas/awesome-markdown/#readme)

## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Ashwin Vishnu has waived all copyright
and related or neighbouring rights to this work. See [LICENSE](LICENSE).

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
