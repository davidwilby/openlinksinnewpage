# openlinksinnewpage Extension For Quarto

With the `openlinksinnewpage` filter [hyperlinks](https://quarto.org/) automatically open in a new page, similarly to adding `{target="_blank"}` to your markdown hyperlinks.

Packaged up as an extension following suggestion by @cscheid on a discussion [here](https://github.com/quarto-dev/quarto-cli/discussions/3169).

This provides an alternative to using the following syntax

```md
[quarto](https://quarto.org/){target="_blank"}
```

if you want all links to be opened in a new page.

## Installing

```bash
quarto add davidwilby/openlinksinnewpage
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

Carry on as usual! Ensure that the following is in your yaml frontmatter:

```yaml
filters:
    - openlinksinnewpage
```

All the links in your quarto document or presentation will open in a new page or tab.

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

