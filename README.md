---
---
---

# \<%= title %\> Format

This is a repository template using Quarto reveal.js used and made by the Global Health Engineering Group:

***GIF***

## Creating a new article

This [Quarto](https://quarto.org/) extension can be installed using the following command

``` bash
quarto use template Global-Health-Engineering/template-quarto-revealjs-theme
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Installation foe existing document

You may also use this format with an existing Quarto project or document. From the Quarto project or document directory, run the following command to install this format:

``` bash
quarto install extension Global-Health-Engineering/template-quarto-revealjs-theme
```

## Usage

To use the format, you can use the format names `iop-pdf` and `iop-html`. For example:

``` bash
quarto render article.qmd --to iop-pdf
```

or in your document yaml

``` yaml
format:
  iop-pdf:
    keep-tex: true    
```

## Format Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).
