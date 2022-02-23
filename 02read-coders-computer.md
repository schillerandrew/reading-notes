> # The Coder's Computer

## Choosing a Text Editor
- The "best" text editor is probably the one that works best for you, not necessarily what others says is good or "the best".
- Text editors are different from word processors and focus more on simple text editing, but also with additional features tailored to coding.
    - Important features are:
        - code completion (assists you as you type)
        - syntax highlighting (different colors and highlighting of distinct parts of your code)
        - variety of themes (so you can pick a look and feel that is best for you)
        - good selection of extensions (the beefier features -- bells and whistles)

### Pre-packaged OS text editors
- Text Edit (Mac)
- Notepad (Windows)
- Gedit (Linux -- others depending on Linux distro)

### Third-party text editors
- Notepad++ = free, Windows-only
- Text Wrangler / BB Edit = Mac-only
- Visual Studio Code = free, all platforms, Emmet shorthand automatically included (popular in web dev community)
- Atom (GitHub)
- Brackets (Adobe) = free, HTML/CSS/JS-only unless you add extensions
- Sublime Text = $70

## The Command Line
- command line (terminal) = text based interface to system, as opposed to a GUI (graphical user interface)
- usually a command is entered first, and output follows
- after the command is arguments, separated by spaces
    - the first argument is also called an option and usually starts with a hyphen `-`

## Useful commands
- `pwd` = print-working-directory
- `ls` = list (what's in the pwd)
    - when path is defined, `/`s are used for absolute path -- without that it's a relative path that is dependent on your current pwd
    - `~` = home directory (`cd` without any arguments goes to home directory)
    - `.` = current directory
    - `..` = parent directory (one above)
    - `ls -a` = shows contents, including hidden files
        - any file or directory that starts with `.` is automatically hidden
- `file PATH` = tells you type of file specified in PATH

## Linux rules
- everything is a file, even directories
- files can have any extension or even no extension
- case-sensitive
- spaces in filenames (and directories) can be a problem

> ### [Back to homepage](https://schillerandrew.github.io/reading-notes/)
