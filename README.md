# Base16 **Leaf Tomorrow** Dark Theme for VSCode

☘️ Less red, more green + tons of small improvements 👽🥑🔋  
Since _Tomorrow_ just felt too red to me, I replaced that color with a nice green.
Out came a less red and more green version of Base16 Tomorrow Dark Theme with some modifications in secondary colors.
Now also optimised for writing distraction-free in markdown. It displays **bold bold** and _italic in italics_.  

![screenshot](screenshot.gif)

Based on _Base16 Tomorrow Dark+_ Theme by Shurelia.


---

To install the Theme, search for 'Leaf Tomorrow' in the extensions panel.

[Theme in the VSCode marketplace](https://marketplace.visualstudio.com/items?itemName=swjh.base16-leaf-tomorrow-vscode)

[Repository on github](https://github.com/simonhermann/base16-leaf-tomorrow-vscode-theme)
<br>

---

## Recommendations

Recommended fonts are Fira Code or Source Code Pro.
For Markdown, [iA Writer Duospace](https://github.com/iaolo/iA-Fonts/tree/master/iA%20Writer%20Duospace) is amazing.  
Matching file icon themes are "Seti" or "File icons".

### Settings:

```json
    "editor.fontFamily": "'Fira Code', 'Source Code Pro', monospace",
    "editor.renderWhitespace": "boundary",
    "window.menuBarVisibility": "hidden",
    "editor.cursorBlinking": "phase",
    "editor.minimap.renderCharacters": false,
    "editor.minimap.showSlider": "always",
    "[markdown]": {
        "editor.wordWrap": "bounded",
        "editor.wordWrapColumn": 84,
        "editor.fontFamily": "'iA Writer Duospace'",
        "editor.fontSize": 16.5,
        "editor.lineHeight": 29,
        "editor.matchBrackets": false,
        "editor.lineNumbers": "off",
    },
```

Minimal, but still useful color setting for [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) and [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) plugins:
```json
  "indentRainbow.colors": [
    "rgba(16,16,16,0.1)",
    "rgba(16,16,16,0.4)",
    "rgba(16,16,16,0.8)",
    "rgba(16,16,16,0.4)"
  ],
  "bracket-pair-colorizer-2.colors": [
    "#f0c674",
    "#b294bb",
    "#81a2be",
  ],
```



