# engineer1.org website

[engineer1.org](https://engineer1.org) is a static website that's built from [markdown](https://en.wikipedia.org/wiki/Markdown) files
using [MkDocs](https://www.mkdocs.org) with [Material](https://squidfunk.github.io/mkdocs-material)

If you need to modify the web site, be sure you've got [poetry](https://python-poetry.org) installed on your system and then install the necessary project dependencies:

```bash
poetry install
```

Once you've got everything installed, you can start to create and edit markdown files.
If you'd like to preview the web site while you write locally, you can run:

```bash
poetry run mkdocs serve
```

and that will allow you to view everything locally at http://127.0.0.1:8000