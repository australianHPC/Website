# AustralianHPC.org website repository

## Prequisites for developing

You will need git, an editor, mkdocs (latest version) and the material theme for makedocs.

```
pip install mkdocs
pip install mkdocs-material
```

## Developing

As ever it is best to develop on a branch when using git, so make a branch for each bit of the website you're working on.

If you run `mkdocs serve` from the directory you will be able to browse the website live at http://127.0.0.1:8000/ and it should auto-reload pages as you edit.

Once you are happy then commit it to git with a good commit message and push it up, then you can do a pull request (PR) to get this back into the main tree.

## Documentation resources:

* MkDocs: http://www.mkdocs.org/
* Material theme: https://squidfunk.github.io/mkdocs-material/
