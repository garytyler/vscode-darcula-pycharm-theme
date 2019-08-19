# Darcula PyCharm

![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version/garytyler.darcula-pycharm.svg) ![Downloads](https://vsmarketplacebadge.apphb.com/downloads/garytyler.darcula-pycharm.svg)

Precise implementation of the Darcula PyCharm color scheme, optimized for Python.

## Options

 - **Light GUI** - Replicates default PyCharm's GUI
 - **Dark GUI** - Inspired by PyCharm's GUI

## Customization

To change the base text color, use a snippet like this in your `settings.json`

```json
{
    "editor.tokenColorCustomizations": {
        "[Darcula Pycharm with Dark GUI]": {
            "textMateRules": [
                {
                    "name": "Foreground base syntax",
                    "scope": [
                        "text", // For markup
                        "source", // For code
                    ],
                    "settings": {
                        "foreground": "#FF0000" // Bright red
                    }
                },
            ]
        },
    }
}
```