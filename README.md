# Darcula PyCharm Theme

![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version/garytyler.darcula-pycharm.svg) ![Downloads](https://vsmarketplacebadge.apphb.com/downloads/garytyler.darcula-pycharm.svg)

Replica of PyCharm's 'Darcula' syntax theme, optimized for Python

* Dark and Light GUI options
* RegEx highlighting
* Jinja & Django Template support (See [Template Support](#template-support))
* Overridable base highlight (See [Customization](#syntax-customization))
* Support for many popular languages

 <table>
  <tr>
    <th>Light GUI</th>
    <th>Dark GUI</th>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/garytyler/darcula-pycharm/master/images/light.png"  /></td>
    <td><img src="https://raw.githubusercontent.com/garytyler/darcula-pycharm/master/images/dark.png"  /> </td>
  </tr>
</table>

## Template Support

Use one of these plugins:
* [Jinja plugin](https://marketplace.visualstudio.com/items?itemName=wholroyd.jinja)
* [Better Jinja](https://marketplace.visualstudio.com/items?itemName=samuelcolvin.jinjahtml)
* [Django plugin](https://marketplace.visualstudio.com/items?itemName=batisteo.vscode-django)
* [Django Template plugin](https://marketplace.visualstudio.com/items?itemName=bibhasdn.django-html)

## Syntax Customization

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