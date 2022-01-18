### [Spyder](https://www.spyder-ide.org/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/spyder-ide.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/spyder-ide/archive/master.zip) option and unzip them.

#### Activating theme

For Spyder 4.0.x

1. With Spyder closed, open `~/.spyder-py3/spyder.ini`
2. Find the `[appearance]` section. Add `dracula` to the names variable. For example:

    ```
    ...
    [appearance]
    ...
    names = ['emacs', 'idle', 'monokai', 'pydev', 'scintilla', 'solarized/dark', 'solarized/light', 'spyder', 'spyder/dark', 'tomorrow', 'zenburn', 'dracula']
    ```

3. Append the contents of `dracula.ini` (or the following) from this repo to the end of the `[appearance]` section.

    ```
    dracula/name = Dracula
    dracula/background = #282a36
    dracula/currentline = #3a424a
    dracula/currentcell = #292d3e
    dracula/occurrence = #3a424a
    dracula/ctrlclick = #ff79c6
    dracula/sideareas = #282a36
    dracula/matched_p = #50fa7b
    dracula/unmatched_p = #ff5555
    dracula/normal = ('#f8f8f2', False, False)
    dracula/keyword = ('#8be9fd', False, False)
    dracula/builtin = ('#fab16c', False, False)
    dracula/definition = ('#50fa7b', False, False)
    dracula/comment = ('#6272a4', False, False)
    dracula/string = ('#f1fa8c', False, False)
    dracula/number = ('#bd93f9', False, False)
    dracula/instance = ('#50fa7b', False, True)
    ```

4. The new color scheme will be available in the `Preferences` -> `Appearance` -> `Syntax highlighting theme`
