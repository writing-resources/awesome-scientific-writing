# awesome-scientific-writing [![Awesome][awesome-badge]](https://github.com/sindresorhus/awesome)

Scientific writing can extend beyond LaTeX, made possible by formats,
such as
[Markdown](https://commonmark.org/) (and its many flavours),
[reStructuredText](http://docutils.sourceforge.net/docs/ref/rst/directives.html) and
[Jupyter notebooks](https://jupyter.readthedocs.io/en/latest/).

:gem: means **really _awesome/useful_**.<br />
:bookmark: means ability to **seamlessly cite references**.<br/>
:link: means ability to **refer figures and sections within document**.<br/>
:1234: means ability to write equations in LaTeX.<br/>

## Contents
- [Converters](#converters)
- [Demos](#demos)
    - [Articles and presentations](#articles-and-presentations)
    - [Websites](#websites)
- [Resources](#resources)
- [Other Awesome Lists](#other-awesome-lists)

### Converters
> Converters which can generate LaTeX, HTML or PDF output on demand.

- [academicmarkdown](https://github.com/smathot/academicmarkdown#readme): A
    Python wrapper over Pandoc with specialized extensions to parse certain
    elements, making it a superset of Pandoc flavoured markdown :bookmark:
    :link: :1234:.
- [docutils](http://docutils.sourceforge.net/docs/): Python package which can
    convert reStructuredText into various formats and provides command-line
    tools to do it :link: :1234:.
- [nbconvert](https://nbconvert.readthedocs.io/en/latest/) - Convert Jupyter
    notebooks into `reveal.js` presentations, PDF, HTML, Markdown,
    reStructuredText and more :1234:.
- [pandoc](https://pandoc.org/MANUAL): A Haskell library for converting from
    one markup format to another, and a command-line tool that uses this
    library :gem: :bookmark: :link: :1234:.
- [scholdoc](http://scholdoc.scholarlymarkdown.com/): A fork of Pandoc and the
    reference implementation for ScholarlyMarkdown, a superset of Pandoc
    Markdown flavour :bookmark: :link: :1234:.

### Demos
#### Articles and presentations
- [Katrin Leinweber's Ph.D.
    thesis](https://github.com/katrinleinweber/PhD-thesis/#readme) - An
    automated workflow involving several tools, but primarily Pandoc, `latexmk`
    and AcademicMarkdown.
- [pandoc-starter](https://github.com/jez/pandoc-starter) - Templates for
    articles, beamer presentations etc. using Markdown files and Makefiles for
    getting started with Pandoc.
- [scientific-markdown](https://github.com/JensErat/scientific-markdown/#readme) -
    An example for use of Markdown for scientific publications using Pandoc and
    `latexmk` :gem:.
- [slides](https://github.com/cgroll/slides) - Demo for generating `reveal.js`
    presentations using Pandoc.
- [Writing a  Book With Vim, Restructured Text, and Sphinx](https://www.tompurl.com/2012-11-22-writing-a-book-with-vim.html) - An blog post describing the
    workflow for writing a book using reStructuredText.

#### Websites
- [Compiling a website using Pandoc](http://glines.net/articles/pandoc.html) -
    A blog post and an associated repository demonstrating generating static
    HTML websites.

### Resources
- [Citation Style Language
    (CSL) styles](https://github.com/citation-style-language) - Official
    repository for Citation Style Language (CSL) styles, required by Pandoc.

### Other Awesome Lists
- [Jupyter](https://github.com/markusschanta/awesome-jupyter/#renderingpublishingconversion)
- [Markdown](https://github.com/BubuAnabelas/awesome-markdown/#readme)

## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Ashwin Vishnu has waived all copyright
and related or neighboring rights to this work. See [LICENSE](LICENSE).

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
