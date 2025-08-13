---
title: Forest Health and Old-Growth 🌲
subject: Tutorial
subtitle: Why forest conservation is nuanced
short_title: Forest Health
authors:
  - name: Vance Russell
    affiliations:
      - Executable Books
      - Curvenote
    orcid: 0000-0002-7859-8394
    email: rowan@curvenote.com
license: CC-BY-4.0
keywords: myst, markdown, open-science
abstract: |
  We cite numerous reasons why managing forests is nuanced and have to be adapted to local situations.
kernelspec:
  name: python3
  display_name: Python 3
exports:
  - format: docx
  - format: pdf
    template: volcanica
    article_type: Report
---

# Forest Health and Old-Growth


[](https://doi.org/10.3389/ffgc.2022.979528) old growth paper

Found that policy related to old-growth is complicated ([Carroll 2025](https://doi.org/10.3389/ffgc.2025.1493879)).


## Background

Scientific communication today is designed around print documents and pay-walled access to content. Over the last decade, the open-science movement has accelerated the use of pre-print services and data archives that are vastly improving the accessibility of scientific content. However, these systems are not designed for communicating modern scientific outputs, which encompasses **so much more** than a paper-centric model of the scholarly literature.

> We believe how we share and communicate scientific knowledge should evolve past the status quo of print-based publishing and all the limitations of paper.

The communication and collaboration tools that we are building in the Project Jupyter are built to follow the FORCE11 recommendations [](https://doi.org/10.4230/DagMan.1.1.41). Specifically:

1. rethink the unit and form of scholarly publication;
2. develop tools and technologies to better support the scholarly lifecycle; and
3. add data, software, and workflows as first-class research objects.

By bringing professional, high-quality tools for science communication into the research lifecycle, we believe we can improve the collection and preservation of scholarly metadata (citations, cross-references, annotations, etc.) as well as open up new ways to communicate science with interactive figures & equations, computation, and reactivity.

The tools that are being built by the Project Jupyter are focused on introducing a new Markup language, MyST (Markedly Structured Text), that works seamlessly with the Jupyter community to enhance and promote a new path to document creation and publishing for next-generation scientific textbooks, blogs, and lectures. Our team is currently supported by the [Sloan Foundation](https://sloan.org), ([Grant #9231](https://sloan.org/grant-detail/9231)).

MyST enables rich content generation and is a powerful format for scientific and technical communication. JupyterBook uses MyST and has broad adoption in publishing tutorials and educational content focused around Jupyter Notebooks.

> The components behind Jupyter Book are downloaded 30,000 times a day, with 750K downloads last month.

The current toolchain used by [JupyterBook] is based on [Sphinx], which is an open-source documentation system used in many software projects, especially in the Python ecosystem. `mystjs` is a similar tool to [Sphinx], however, designed specifically for scientific communication. In addition to building websites, `mystjs` can also help you create scientific PDFs, Microsoft Word documents, and JATS XML (used in scientific publishing).

`mystjs` uses existing, modern web-frameworks in place of the [Sphinx] build system. These tools come out-of-the-box with prefetching for faster navigation, smaller network payloads through modern web-bundlers, image optimization, partial-page refresh through single-page application. Many of these features, performance and accessibility improvements are difficult, if not impossible, to create inside of the [Sphinx] build system.

In 2022, the Executable Books team started work to document the specification behind the markup language, called [myst-spec](https://github.com/jupyter-book/myst-spec), this work has enabled other tools and implementations in the scientific ecosystem to build on MyST (e.g. [scientific authoring tools](https://curvenote.com/for/writing), and [documentation systems](https://blog.readthedocs.com/jupyter-book-read-the-docs/)).

The `mystjs` ecosystem was developed as a collaboration between [Curvenote], [2i2c] and the [ExecutableBooks] team. The initial version of `mystjs` was originally release by [Curvenote] as the [Curvenote CLI](https://curvenote.com/docs/cli) under the MIT license, and transferred to the [ExecutableBooks] team in October 2022. The goal of the project is to enable the same rich content and authoring experiences that [Sphinx] allows for software documentation, with a focus on web-first technologies (Javascript), interactivity, accessibility, scientific references (e.g. DOIs and other persistent IDs), professional PDF outputs, and JATS XML documents for scientific archiving.
