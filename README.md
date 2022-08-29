# SportRxiv Article Template

This is a Quarto template that assists you in creating a manuscript for the SportRxiv preprint server.

## Creating a New Article

You can use this as a template to create an article for an AFT journal. To do this, use the following command:

```bash
quarto use template smnnlt/sportrxiv
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension smnnlt/sportrxiv
```

## Usage

To use the format, you can use the format names `aft-pdf` and `aft-html`. For example:

```bash
quarto render article.qmd --to sportrxiv-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  sportrxiv-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at <https://smnnlt.github.io/sportrxiv/>
