# My Zed Preferences

## macOS

On a new Mac, install Zed. In Finder, press **Shift + Command + G** and enter `~/.config/zed/`. Create the folder if needed, then copy these files into it:

- `settings.json` → `~/.config/zed/settings.json`
- `keymap.json` → `~/.config/zed/keymap.json`

If either file already exists, merge the relevant settings or key bindings to preserve your preferences.

## Windows

On a new Windows PC, install Zed. Press **Windows + R**, enter `%APPDATA%\Zed\`, and press **Enter**. If the folder does not exist, open `%APPDATA%` and create a folder named `Zed`, then copy these files into it:

- `settings.json` → `%APPDATA%\Zed\settings.json`
- `keymap.json` → `%APPDATA%\Zed\keymap.json`

If either file already exists, merge the relevant settings or key bindings to preserve your preferences.

In your Windows copy of `keymap.json`, change `cmd-t` to `ctrl-t` and keep the `file_finder::Toggle` action so **Ctrl + T** opens File Finder.
