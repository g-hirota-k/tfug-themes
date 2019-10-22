# Marp TFUG Theme

This is a slide theme for [Marpit](https://github.com/marp-team/marpit)

## Example

[example.pdf](example.pdf) is the result of [example.md](example.md).

<embed src="example.pdf" width="600" alt="pdf" pluginspage="http://www.adobe.com/products/acrobat/readstep2.html">

## Usage

### With VSCode

TFUG Theme is available at <https://ohtaman.github.io/marp/themes/tfug/theme.css>.
You can register the theme as follows.

1. Install the extension: [marp-vscode](https://github.com/marp-team/marp-vscode)
2. Add the url to the .vscode/settings.json

```json
{
  "markdown.marp.themes": [
    "https://ohtaman.github.io/marp/themes/tfug/theme.css"
  ]
}
```

### With Marp CLI

Prease clone this repository and run `marp-cli` as follows

```bash
$ git clone https://github.com/ohtaman/tfug-themes.git
$ npx @marp-team/marp-cli --html --allow-local-files --theme <path_to_the_theme.css> --pdf <path_to_the_md_file>
```

## Example
