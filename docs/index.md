# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://mkdocs.org).

## Commands

- `mkdocs new [dir-name]` - Create a new project.
- `mkdocs serve` - Start the live-reloading docs server.
- `mkdocs build` - Build the documentation site.
- `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
        js/
            embed.js                # Microsoft PXT code blocks rendering.
            jquery-3.4.1.min.js     # Material theme rendering.
        css/
            extra.css               # Extra styles for Material theme.

## MakeCode Blocks sample

```blocks
basic.forever(function () {
    basic.showNumber(0)
})
```
