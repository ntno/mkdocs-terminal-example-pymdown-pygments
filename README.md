# mkdocs-terminal-example-pymdown-pygments

This repository is used to publish an example MkDocs site to GitHub pages.  The site demonstrates how to enable build-time code highlighting with the [Pygments] library and [PyMdown Extensions].

[Pygments]: https://pygments.org/
[PyMdown Extensions]: https://facelessuser.github.io/pymdown-extensions/

## Site

[ntno.github.io/mkdocs-terminal-example-pymdown-pygments](https://ntno.github.io/mkdocs-terminal-example-pymdown-pygments/)

## Source Code

The source code of the site is located in the `ntno/mkdocs-terminal` repository in the [tests/examples/pymdown-pygments](https://github.com/ntno/mkdocs-terminal/tree/main/tests/examples/pymdown-pygments) subfolder.

## CI/CD

A [GitHub Action workflow](https://github.com/ntno/mkdocs-terminal/actions/workflows/pages-deploy-example-site.yml) in the `ntno/mkdocs-terminal` repository updates this site's static files in the [`gh-pages` branch](https://github.com/ntno/mkdocs-terminal-example-pymdown-pygments/tree/gh-pages).