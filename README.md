# md2html-template-for-pandoc

## About

This template is to style when convert files from markdown to html on [Pandoc](http://pandoc.org/index.html).
And This template is referring of [github.css](https://gist.github.com/andyferra/2554919).

## Setup

1. Please, place the "md2html.html" to `~/.pandoc/template/`.
2. Select the command option when you execute pandoc. Like a Example.

### Example

```
pandoc -f markdown -t html --template=md2html README.md > README.html
```
