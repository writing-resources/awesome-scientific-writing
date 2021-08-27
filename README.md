# Awesome Scientific Writing [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome)

> Scientific writing can extend beyond LaTeX, made possible by formats,
> such as
> [Markdown](https://daringfireball.net/projects/markdown/) (and its many flavours),
> [reStructuredText](https://docutils.sourceforge.io/rst.html) and
> [Jupyter notebooks](https://jupyter.org/).

:bookmark: means ability to **seamlessly cite references**.

:link: means ability to **cross-reference figures and sections within the
document**.

## Contents

- [Word Processors](#word-processors)
- [Bibliography](#bibliography)
- [Illustrations](#illustrations)
- [Converters and Filters](#converters-and-filters)
- [Spell Checking and Linting](#spell-checking-and-linting)
- [Templates](#templates)
  - [Articles](#articles)
  - [Presentations](#presentations)
  - [Books](#books)
- [Tutorials](#tutorials)
- [Other Lists](#other-lists)

## Word Processors

- [Atom](https://atom.io) - Popular IDE with Markdown support.
  - [Markdown Preview Enhanced for Atom](https://github.com/shd101wyy/markdown-preview-enhanced) - Pandoc
    integration and utilities for Atom.
  - [Autocomplete BibTeX for Atom](https://github.com/apcshields/autocomplete-bibtex) - BibTeX support for Atom.
- [Marktext](https://marktext.app/) - Markdown text editor.
- [R Studio](https://github.com/rstudio/rstudio) - IDE for R.
  - [bookdown](https://github.com/rstudio/bookdown) - R package to facilitate writing books and long-form articles, reports with R Markdown :bookmark: :link:.
  - [R Markdown](https://rmarkdown.rstudio.com/) - R package to write R next to Markdown
   :bookmark:
   :link:.
- [Vim](https://www.vim.org/) - Command line text editor.
  - [fzf-bibtex](https://github.com/msprev/fzf-bibtex/#readme) - BibTeX source
    with Vim integration which uses fzf (a fuzzy finder implemented in Go).
  - [vim-pandoc](https://github.com/vim-pandoc/vim-pandoc) - Pandoc integration and utilities for Vim.
  - [vim-pandoc-syntax](https://github.com/vim-pandoc/vim-pandoc-syntax) - Pandoc syntax highlighting for Vim.
- [Visual Studio Code](https://code.visualstudio.com/) - Popular IDE with Markdown support.
  - [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown/#readme) - Extension for enhanced
    Markdown support in VSCode, such as preview and auto completion to name a few.
  - [Citation Picker for Zotero](https://marketplace.visualstudio.com/items?itemName=mblode.zotero) :bookmark:
  - [Pandoc Citer](https://marketplace.visualstudio.com/items?itemName=notZaki.pandocciter) - autocompletion of citations stored in a bibtex file :bookmark:
- [Zettlr](https://www.zettlr.com/) - Markdown editor which
   integrates CSL, BibLaTeX, Pandoc and many other tools
   :bookmark: :link:.

## Bibliography

Reference managers to generate citations, BibTeX, and BibLaTeX files.

- [Citation Style Language (CSL) styles](https://editor.citationstyles.org/) - Crowdsourced
  repository with over 9000 free CSL citation styles and an online
  editor to create new ones.
- [JabRef](https://www.jabref.org/) - Open source bibliography reference manager.
- [Zotero](https://www.zotero.org/) - FOSS tool to collect, organize, cite, and
  share research.
  - [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) - Enhanced
    BibTeX / BibLaTeX integration for Zotero.
  - [ZotFile for Zotero](http://zotfile.com/) - Enhanced PDF file management for Zotero.
- [ZoteroBib](https://zbib.org/) - Online bibliography reference manager.

## Illustrations

Drawing illustrations themselves has driven many a scientist mad. Fortunately,
there are formal languages with which one can create beautiful graphics.

- [diagrams.net](https://www.diagrams.net/) - Open source, online, desktop and
  container deployable diagramming software.
- [graphviz](https://graphviz.org/) - Visualization software for graphs and
  networks which uses a domain-specific DOT language.
- [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/) - Define simple diagrams instead of drawing them.
- [Vega Lite](https://vega.github.io/vega-lite/examples/) - Define charts and more complex diagrams.
- [PlantUML](https://plantuml.com/) - Define UML diagrams instead of drawing them.

## Converters and Filters

Supplementary files and tools.

- [Cicero](https://cicero.xyz/) - Python package which renders HTML presentations
  from Markdown source using remark or reveal.js :link:.
- [docutils](https://docutils.sourceforge.io/docs/) - Python package which can
  convert reStructuredText into various formats and provides command-line
  tools to do it :link:.
- [Jupyter Book](https://jupyterbook.org/) - A static site generator which converts
  a collection of CommonMark, MyST markdown and Jupyter notebooks into a HTML website.
- [MyST](https://myst-parser.readthedocs.io/en/latest/) - Markedly Structured Text,
  a superset of CommonMark markdown with reStructuredText like features.
- [nbconvert](https://nbconvert.readthedocs.io/en/latest/) - Convert Jupyter
  notebooks into `reveal.js` presentations, PDF, HTML, Markdown,
  reStructuredText and more.
  - [bookbook](https://github.com/takluyver/bookbook/#readme) - Experimental Python
    package which extends `nbconvert` and adds the ability to cross reference
    within and across notebooks :link:.
  - [ipypublish](https://github.com/chrisjsewell/ipypublish/#readme) - Workflow for
    creating and editing publication ready scientific reports and presentations,
    from one or more Jupyter Notebooks, without leaving the browser :bookmark:
    :link:.
- [pandoc](https://pandoc.org/MANUAL) - Haskell library for converting from
  one markup format to another, and a command-line tool that uses this
  library :bookmark: :link:.
  - [Academic Markdown](https://github.com/smathot/academicmarkdown#readme) - Python wrapper over Pandoc with specialized extensions to parse certain
    elements, making it a superset of Pandoc Markdown flavour :bookmark:
    :link:.
  - [Pandoc filters](https://github.com/jgm/pandoc/wiki/Pandoc-Filters) - List of
    addons to pandoc which implement extra features such as citations and
    cross-references.
  - [Panflute](http://scorreia.com/software/panflute/) - Pythonic alternative
    to John MacFarlane's pandocfilters.

## Spell Checking and Linting

- [GNU Aspell](http://aspell.net/) - Command line spell checker.
- [Hunspell](http://hunspell.github.io/) - Command line spell checker.
- [LanguageTool](https://languagetool.org/) - Open source grammar, style and
 spell Checker.
- [Markdown lint tool](https://github.com/markdownlint/markdownlint) - Markdown linter.
- [proselint](http://proselint.com/) - Linter for prose.
- [remarklint](https://github.com/remarkjs/remark-lint) - Markdown linter.
- [restructuredtext-lint](https://github.com/twolfson/restructuredtext-lint) - reStructuredText linter.
- [textlint](https://textlint.github.io/) - Pluggable linting tool for text
 and Markdown.
- [textidote](https://sylvainhalle.github.io/textidote/) - Spelling, grammar and
 style checking on LaTeX documents.
- [Vale](https://errata-ai.github.io/vale/) - Free, open-source linter for
 prose built with speed and extensibility in mind.
- [write-good](https://github.com/btford/write-good) - Naive linter for English
 prose.

## Templates

Reusable minimalist examples.

### Articles

- [Pandoc Markdown-LaTeX
   Boilerplate](https://github.com/davecap/markdown-latex-boilerplate/#readme) - Demonstrate
   how to integrate Pandoc with an existing LaTeX template which
   requires some boilerplate code (i.e. LaTeX preamble), thus avoiding the
   `latexmk` dependency.
- [scientific-markdown](https://github.com/JensErat/scientific-markdown/#readme) - Example
   for use of Markdown for scientific publications using Pandoc and
   `latexmk`.
- [Steve's R Markdown Templates](https://github.com/svmiller/svm-r-markdown-templates/) - Academic manuscript, memos, Beamer presentation, syllabus and CV.

### Presentations

- [pandoc-starter](https://github.com/jez/pandoc-starter/#readme) - Templates for
   articles, Beamer presentations etc. using Markdown files and Makefiles for
   getting started with Pandoc.
- [slides](https://github.com/cgroll/slides/#readme) - Demo for generating `reveal.js`
   presentations using Pandoc.

### Books

- [bookdown-demo](https://github.com/rstudio/bookdown-demo/#readme) - Minimal
   example of a book based on R Markdown and bookdown.
- [Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template) - Clean academic pandoc LaTeX template.
- [Template for writing a PhD thesis in
   Markdown](https://github.com/tompollard/phd_thesis_markdown#readme) - Clean
   organization of files to provide a framework for writing a PhD thesis in
   mostly Markdown with a little bit of LaTeX, and compiled with Pandoc.

## Tutorials

How to generate articles and presentations for scientific purposes.

- [Book on Riemann solvers](https://github.com/clawpack/riemann_book/#readme) - This
   example uses a custom `nbconvert` template and shows how to store your
   notebooks with no output (for version control) while automatically executing
   them before running `bookbook`, so that PDF and HTML versions include the
   output.
- [Dennis Tenen and Grant Wythoff](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) - Sustainable Authorship in Plain Text using Pandoc and Markdown.
- [Katrin Leinweber's Ph.D.
   thesis](https://github.com/katrinleinweber/PhD-thesis/#readme) - Automated
   work flow involving several tools, but primarily Pandoc, `latexmk` and
   Academic Markdown.
- [Scott Selisker](http://u.arizona.edu/~selisker/post/workflow/) - Plain Text Workflow for Academic Writing with Atom.
- [Teaching and learning with
   Jupyter](https://github.com/jupyter4edu/jupyter-edu-book/#readme) - Book
   written in R Markdown, bookdown and also rendered as HTML, PDF and
   EPUB.
- [Writing scientific papers for ACPD using Emacs
   Org-mode](https://www.draketo.de/english/emacs/writing-papers-in-org-mode-acpd) - Detailed
   tutorial on authoring a paper by seamlessly integrating with LaTeX
   commands within Org-mode.

## Other Lists

- [Awesome Jupyter](https://github.com/markusschanta/awesome-jupyter/#renderingpublishingconversion)
- [Awesome LaTeX](https://github.com/egeerardyn/awesome-LaTeX/#readme)
- [Awesome Markdown](https://github.com/BubuAnabelas/awesome-markdown/#readme)
- [Delightful Open Science](https://codeberg.org/teaserbot-labs/delightful-open-science)

### Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
