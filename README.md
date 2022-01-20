# Contracts

Standard contracts that we use.

## Markdown to PDF

We've used the [markdown-pdf][] Atom editor package to convert the Markdown documents to PDF.

From the command line it's also possible to use pandoc and xelatex

```
brew install pandoc basictex

pandoc src/standard-14days.md --pdf-engine=xelatex -o contract.pdf
```

[markdown-pdf]: https://atom.io/packages/markdown-pdf
