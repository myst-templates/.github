# MyST Templates

A community curated collection of [MyST Markdown](https://mystmd.org) compatible templates. Learn how [use the LaTeX templates](https://mystmd.org/guide/creating-pdf-documents), in your MyST Markdown frontmatter, add:

```yaml
---
title: My Document
exports:
  - format: pdf
    template: arxiv_two_column
---
```

Then from the command line:

```bash
myst build my-document.md
```

The templates in this organization allow `myst` to export markdown files as typeset, formatted documents using PDF, LaTeX or Word. Templates can expose data-driven options for customization ensuring the final documents comply with author submission guidelines provided by a particular journal, conference organizer or university. Note that exporting to PDF will require LaTeX to be installed locally, [learn more](https://mystmd.org/guide/quickstart-myst-documents).

## Contributing

MyST welcomes contributions of new templates, or improvements to any of our curated templates. To get started:

- 📝 [open an issue](https://github.com/myst-templates/templates/issues) - tell us about the template you'd like added. Provide a link to the template if it's online, or attach the files if you have them.
- 🏋🏽‍♀️ [create your own template](https://mystmd.org/jtex/create-a-latex-template) - Learn how to create your own template in a few easy steps!
- 🤝 [contribute a template](https://mystmd.org/jtex/contribute-a-template) - Even if it's partial or barely started we'll help test and get it over the line.

LaTeX templates in this organization can be tested and used in conjunction with [jtex](https://mystmd.org/jtex) a command line tool that helps validate and template your LaTeX documents.

For more details on contributing, learning about the structure of templates specifically and how to build one. See the [Contributors Guide](https://mystmd.org/jtex/contribute-a-template).

## Templates

| Title (`id`)                                          | Kind | Repository                                                                                       | CI                                                                                                                                                                                                                |
| :---------------------------------------------------- | :--- | :----------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default Docx Template (`default`)                     | docx | [default](https://github.com/myst-templates/docx_default)                                        | [![](https://github.com/myst-templates/docx_default/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/docx_default/actions/workflows/jtex.yml)                                             |
| Curvenote Docx Template (`curvenote`)                 | docx | [curvenote](https://github.com/myst-templates/curvenote_docx)                                    | [![](https://github.com/myst-templates/curvenote_docx/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/curvenote_docx/actions/workflows/jtex.yml)                                         |
| AGU Journal (`agu2019`)                               | tex  | [agu2019](https://github.com/myst-templates/agu2019)                                             | [![](https://github.com/myst-templates/agu2019/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/agu2019/actions/workflows/jtex.yml)                                                       |
| arXiv (NIPS Style) (`arxiv_nips`)                     | tex  | [arxiv_nips](https://github.com/myst-templates/arxiv_nips)                                       | [![](https://github.com/myst-templates/arxiv_nips/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/arxiv_nips/actions/workflows/jtex.yml)                                                 |
| arXiv (Two Column) (`arxiv_two_column`)               | tex  | [arxiv_two_column](https://github.com/myst-templates/arxiv_two_column)                           | [![](https://github.com/myst-templates/arxiv_two_column/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/arxiv_two_column/actions/workflows/jtex.yml)                                     |
| EarthArXiv (`eartharxiv`)                             | tex  | [eartharxiv](https://github.com/myst-templates/eartharxiv)                                       | [![](https://github.com/myst-templates/eartharxiv/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/eartharxiv/actions/workflows/jtex.yml)                                                 |
| Frontiers (`frontiers`)                               | tex  | [frontiers](https://github.com/myst-templates/frontiers)                                         | [![](https://github.com/myst-templates/frontiers/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/frontiers/actions/workflows/jtex.yml)                                                   |
| Physiome Journal (`physiome`)                         | tex  | [physiome](https://github.com/myst-templates/physiome)                                           | [![](https://github.com/myst-templates/physiome/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/physiome/actions/workflows/jtex.yml)                                                     |
| SPIE Proceedings (`spie_proceedings`)                 | tex  | [spie_proceedings](https://github.com/myst-templates/spie_proceedings)                           | [![](https://github.com/myst-templates/spie_proceedings/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/spie_proceedings/actions/workflows/jtex.yml)                                     |
| Volcanica (`volcanica`)                               | tex  | [volcanica](https://github.com/myst-templates/volcanica)                                         | [![](https://github.com/myst-templates/volcanica/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/volcanica/actions/workflows/jtex.yml)                                                   |
| Curvenote Default (`curvenote`)                       | tex  | [curvenote](https://github.com/myst-templates/curvenote)                                         | [![](https://github.com/myst-templates/curvenote/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/curvenote/actions/workflows/jtex.yml)                                                   |
| EGU Copernicus (`egu_copernicus`)                     | tex  | [egu_copernicus](https://github.com/myst-templates/egu_copernicus)                               | [![](https://github.com/myst-templates/egu_copernicus/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/egu_copernicus/actions/workflows/jtex.yml)                                         |
| MDPI Journal (`mdpi`)                                 | tex  | [mdpi](https://github.com/myst-templates/mdpi)                                                   | [![](https://github.com/myst-templates/mdpi/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/mdpi/actions/workflows/jtex.yml)                                                             |
| Plain LaTeX (`plain_latex`)                           | tex  | [plain_latex](https://github.com/myst-templates/plain_latex)                                     | [![](https://github.com/myst-templates/plain_latex/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/plain_latex/actions/workflows/jtex.yml)                                               |
| Plain LaTeX Book (`plain_latex_book`)                 | tex  | [plain_latex_book](https://github.com/myst-templates/plain_latex_book)                           | [![](https://github.com/myst-templates/plain_latex_book/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/plain_latex_book/actions/workflows/jtex.yml)                                     |
| LaPreprint (`lapreprint`)                             | tex  | [lapreprint](https://github.com/myst-templates/lapreprint)                                       | [![](https://github.com/myst-templates/lapreprint/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/lapreprint/actions/workflows/jtex.yml)                                                 |
| ISPRS - Full Paper (`isprs`)                          | tex  | [isprs](https://github.com/myst-templates/isprs)                                                 | [![](https://github.com/myst-templates/isprs/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/isprs/actions/workflows/jtex.yml)                                                           |
| Physical Review Journals (`physical_review_journals`) | tex  | [physical_review_journals](https://github.com/dressedfez/myst_template_physical_review_journals) | [![](https://github.com/dressedfez/myst_template_physical_review_journals/actions/workflows/jtex.yml/badge.svg)](https://github.com/dressedfez/myst_template_physical_review_journals/actions/workflows/jtex.yml) |
| Computers & Geosciences (`cageo`)                     | tex  | [cageo](https://github.com/myst-templates/cageo)                                                 | [![](https://github.com/myst-templates/cageo/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/cageo/actions/workflows/jtex.yml)                                                           |
| Springer (`springer`)                                 | tex  | [springer](https://github.com/myst-templates/springer)                                           | [![](https://github.com/myst-templates/springer/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/springer/actions/workflows/jtex.yml)                                                     |
| Book Theme (`book-theme`)                             | site | [book-theme](https://github.com/myst-templates/book-theme)                                       | [![](https://github.com/myst-templates/book-theme/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/book-theme/actions/workflows/jtex.yml)                                                 |
| Article Theme (`article-theme`)                       | site | [article-theme](https://github.com/myst-templates/article-theme)                                 | [![](https://github.com/myst-templates/article-theme/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/article-theme/actions/workflows/jtex.yml)                                           |
