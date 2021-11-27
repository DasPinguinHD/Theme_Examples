# Oasis Themes
How OASIS Themes work:

There are three types of Themes

- Single Color
- Multi Color
- Gradient

---

You can specify Colors in 2 ways

- as RGB, e.g. `rgb(255,255,255)`
- as HEX, e.g. `#FFFFFF`

---

1. `Single Color Themes`

```toml
Type = "Single"
[Colors]
Color = ""
Background = ""
```

---

2. `Multi Color Themes`

```toml
Type = "Multi"
[Colors]
First = ""
Second = ""
Third = ""
Fourth = ""
Fifth = ""
Background = ""
```

---

3. `Gradient Color Themes`

```toml
Type = "Gradient"
[Colors]
First = ""
Last = ""
Background = ""
```

---
How to implement the new custom theme:

- Create a `.toml` (for example `MySuperCoolTheme.toml`) file in your Themes folder and copy an example from this tutorial.
- Replace the color codes with your own.
- Enter the theme file's name in your `config.toml` file and don't forget to restart the Selfbot.
