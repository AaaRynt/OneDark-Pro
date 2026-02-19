# One Dark Pro enhance

## Enhance the visual display of `markdown` and webview

- init:
![init](./screenshots/2026-02-19_14-21-03.png)

- enhance:
![enhance](./screenshots/2026-02-19_14-24-14.png)

## Remove the italitic on JSX attribute

## setting.json

Change the display Boolean values in `setting.json`

```json
"editor.tokenColorCustomizations": {
  "[One Dark Pro]": {
    "textMateRules": [
      {
        "settings": {
          "foreground": "#00ff00",
        },
        "scope": "constant.language.boolean.true",
      },
      {
        "settings": {
          "foreground": "#ff0000",
        },
        "scope": "constant.language.boolean.false",
      },
    ],
  },
},
