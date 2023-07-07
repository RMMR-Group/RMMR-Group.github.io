---
title: Writing Documentation
layout: page
nav_order: 2
---

## What to document

The general philosophy is to document anything that you think someone else might have to do after you, and that took you more than a simple google search to figure out. In general, it's better to err on the side of writing a sketchy note, rather than waiting until you have time to write perfect documentation (and then never getting around to writing the perfect document).

If you find documentation that is out of date, please do try to update it. Everything is version controlled, so no information is ever lost when you make an edit. Be bold!

## Editing the docs

The repos for the documentation is here: [https://github.com/RMMR-Group/rmmr_group_docs](https://github.com/RMMR-Group/rmmr_group_docs)

In general we're not requiring pull requests, etc. as we're not too worried about "breaking" changes to the documentation. Just edit directly on the `main` branch and commit when you're done. Please review your edits on the live website (changes can take a few minutes to appear after you commit them), and fix anything that's not right, so we can keep the docs tidy.

## Structure of the docs

We're using `mkdocs` to generate the documentation. You can find the manual for `mkdocs` here:
[https://www.mkdocs.org](https://www.mkdocs.org)

Documentation is written in Markdown, which is designed to be pretty lightweight. You can find a description of the syntax here:
[https://www.markdownguide.org](https://www.markdownguide.org)

At the root level you'll find a file named `mkdocs.yml`, which defines the table of contents for the documentation. If you add a new file, be sure to add it here so it becomes part of the docs.
