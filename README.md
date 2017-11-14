# Godot syntax themes

![Screenshot](https://archive.hugo.pro/.public/godot-syntax-themes.png)

*The Darcula theme in action.*

This repository contains many syntax themes for Godot, for use in the built-in
script editor. You need Godot 2.1 to use them, but these also work in
the current 3.0 development builds.

## Available themes

- Atom Dark
- Darcula
- Gruvbox Dark
- Metro
- Monokai
- One Dark
- Solarized Dark

## Installation

Place the `.tet` files in your Godot text editor theme directory:

- On Linux and macOS: `$HOME/.godot/text_editor_themes/`
- On Windows: `%APPDATA%\Godot\text_editor_themes\`

To change the theme:

- **On Godot 2.1:** Open a project in Godot, then click on the upper-right
   **Settings** → **Editor Settings** → **Text Editor**. You should now be able
   to choose the desired theme.

- **On Godot 3.0:** Open a project in Godot, then click on **Editor** in the top
  menu, then go to the **Editor Settings** then **Text Editor**. You should now be
  able to choose the desired theme.

**Tip:** You can clone this Git repository directly into the text editor themes
path, if the destination folder does not exist, using the following Git command:

```bash
# On Linux and macOS
git clone https://github.com/Calinou/godot-syntax-themes.git "$HOME/.godot/text_editor_themes"

# On Windows
git clone https://github.com/Calinou/godot-syntax-themes.git "%APPDATA%\Godot\text_editor_themes"
```

## License

Copyright © 2016-2017 Hugo Locurcio and contributors

Files in this repository are licensed under CC0 1.0 Universal,
see [LICENSE.md](/LICENSE.md) for more information.
