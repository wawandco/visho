# Visho

![Logo](https://raw.githubusercontent.com/wawandco/visho/main/assets/visho.png)

Visho is a VSCode extension that provides tooling for the [Plush](https://github.com/gobuffalo/plush) templating language. 

## Features

### Syntax highlighting
This extension provides syntax highlighting for the Plush language.

![Preview](https://raw.githubusercontent.com/wawandco/visho/main/assets/syntax-highlight.png)
### Code snippets

Visho provides a set of code snippets for the most common plush tags and functions.

- `pif` adds an if block
- `pie` adds an if/else block
- `pm` adds a map variable definition
- `pa` adds an array/slice variable definition
- `pa` adds an array/slice variable definition
- `pfor` adds a for block
- `pform` adds a form block
- `pformf` adds a form_for block 
- `pinp` adds a plush input tag
- `pta` adds a plush text area
- `pslc` adds a plush select tag
- `pch` adds a plush checkbox tag
- `pe` adds a plush expression (`<% content %>`)
- `pt` adds a print tag (`<%= content %>`)

Additionally these can be used with the `pl` prefix instead of `p` (e.g. `plif` instead of `pif`)

## FAQ

### Why is it called Visho?

Visho is the combination of Visual Studio Code and Plush. We just added an O at the end to make it sound cooler.

### How do I make Emmet work with Visho?

You will need to add the following to your `settings.json` file:

```json
"emmet.includeLanguages": {
    "plush": "html"
}
```

## Copyright

Visho is Copyright © 2022 Wawandco SAS. It is free software, and may be redistributed under the terms specified in the LICENSE file.