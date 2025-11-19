# marp-theme
A marp theme based on [HSMW](https://git.hs-mittweida.de/marp/marp-template-hsmw)

## Exporting

### marp CLI

```sh
git clone https://github.com/promicrobial/marp-theme.git
cd marp-theme

marp example-slides.md --pdf -o example-slides.pdf --allow-local-files --theme-set theme
```

### VS Code/Positron Marp Plugin

Install the [marp plugin](https://github.com/marp-team/marp-vscode) through the extensions store. Add this to `settings.json`

```json
"markdown.marp.themes": [
  "https://raw.githubusercontent.com/promicrobial/marp-theme/refs/heads/main/theme/nord-nc.css",
  "https://raw.githubusercontent.com/promicrobial/marp-theme/refs/heads/main/theme/_hsmw-nc.css",
  "https://raw.githubusercontent.com/promicrobial/marp-theme/refs/heads/main/theme/hsmw-nc.css"
    ],
```