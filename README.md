# OpenPyrojet Website

The OpenPyrojet website is made with [MkDocs](http://www.mkdocs.org).

This repository hosts the source files for building it.

# Pre-requisites

After installing `Python 3`, run:

```bash
pip install mkdocs
```

# Building

Building a new version:

```bash
mkdocs build
```

Trying out the current version locally:

```bash
mkdocs serve
```

# Publishing

After verifying that the changes work with the `mkdocs serve` command, you can build and publish your changes:

```bash
mkdocs build
git add docs/*
git add source/*
git commit -m "Description of changes"
git push
```

Then wait a minute or two until GitHub updates the website.

