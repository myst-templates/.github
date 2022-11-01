# MyST Templates

A community curated collection of [MyST Markdown](https://myst.tools) compatible templates. Learn how [use the LaTeX templates](https://js.myst.tools/guide/creating-pdf-documents), in your MyST Markdown frontmatter, add:

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

The templates in this organization allow `myst` to export markdown files as typeset, formatted documents using PDF, LaTeX or Word. Templates can expose data-driven options for customization ensuring the final documents comply with author submission guidelines provided by a particular journal, conference organizer or university. Note that exporting to PDF will require LaTeX to be installed locally, [learn more](https://js.myst.tools/guide/creating-pdf-documents).

## Contributing

MyST welcomes contributions of new templates, or improvements to any of our curated templates. To get started:

- 📝 [open an issue](https://github.com/myst-templates/templates/issues) - tell us about the template you'd like added. Provide a link to the template if it's online, or attach the files if you have them.
- 🏋🏽‍♀️ [create your own template](https://js.myst.tools/jtex/create-a-latex-template) - Learn how to create your own template in a few easy steps!
- 🤝 [contribute a template](https://js.myst.tools/jtex/contribute-a-template) - Even if it's partial or barely started we'll help test and get it over the line.

LaTeX templates in this organization can be tested and used in conjunction with [jtex](https://js.myst.tools/jtex) a command line tool that helps validate and template your LaTeX documents.

For more details on contributing, learning about the structure of templates specifically and how to build one. See the [Contributors Guide](https://js.myst.tools/jtex/contribute-a-template).

## LaTeX Templates

| Title (`id`)                      | Repository                                                | CI                                                                                                                                                                    |
| :-------------------------------- | :-------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default Docx Template (`default`) | [default](https://github.com/myst-templates/docx_default) | [![](https://github.com/myst-templates/docx_default/actions/workflows/jtex.yml/badge.svg)](https://github.com/myst-templates/docx_default/actions/workflows/jtex.yml) |
