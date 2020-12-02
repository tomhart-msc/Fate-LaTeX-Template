# Fate LaTeX Template

This is a LaTeX template for typesetting documents in the style of Fate Core, in the spirit of the [DnD LaTeX Template](https://github.com/rpgtex/DND-5e-LaTeX-Template) and the [Genesys LaTeX package](https://github.com/c-bec-k/GenesysRPG).

## Building the Example

```
latexmk.exe --pdf --pdflatex=pdflatex example.tex
```

## Using the Stylesheet

The stylesheet has only been tested with the `book` class. You can drop the `fate.sty` file into your project directory.

## Bugs

The `sidebar` environment often collides with other text. Using `wrapfig` manually around a `sidebarBox` may work better but I need to experiment with it more.