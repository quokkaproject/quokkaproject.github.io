# QUOKKA CMS Website and Documentation

this repository is the main quokkaproject.org website and its documentation.

## How to contribute to website

Fork and clone this repository in order to make contributions to the website, design, style, examples etc. Any good suggestions will be taken.

## How to contribute to documentation

Fork this repository, clone locally, create a virtualenv

```bash
mkvirtualenv quokkadev
```

Install mkdocs

```bash
pip install mkdocs
```

Access the folder containing mkdocs.yml file (the root of this repository)

use the following command to serve the documentation in your browser

```bash
mkdocs serve
```

Now you can access ```localhost:8000``` and see the documentation website locally

Make the contributions using the markdown files under /docs folder

> /docs are source and /documentation are the built docs

> You can use an .md editor to write, I suggest ATOM from github, it has a nice markdown previewer plugin

After making your changes run the following command

```
mkdocs build --clean
```

commit and send your Pull Request
