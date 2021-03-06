# KV for Notepad++
Syntax Highlighting for [Kivy](https://kivy.org) files in Notepad++

<img src="https://raw.githubusercontent.com/KeyWeeUsr/KV-for-NotepadPP/master/screen.png" width=800></img>

### What is it?
In Notepad++ you can define your own language syntax highlighting which is then saved to an `.xml` file and that's it. A syntax highlighting for [KV language](https://kivy.org/docs/guide/lang.html). The highlighting works in recent versions - tested on `6.9.1`.

### How to use it
 - Clone the repo or download [KVlang.xml](https://raw.githubusercontent.com/KeyWeeUsr/KV-for-NotepadPP/master/KVlang.xml) file
 - Open Notepad++
 - Go to:
    - `Language`
    - `Define your language`
    - `Import`
    - Select the `.xml` file you've downloaded
 - Close and restart Notepad++

If you don't want to restart, close & open `.kv` files, highlighting will become active, however you won't see `Kivy` in `Language` menu until the restart.

### How to contribute
- Read [notepad++ UDL docs](http://docs.notepad-plus-plus.org/index.php/User_Defined_Languages)
- Clone repo
- Import `.xml`
- Make changes
- Export `.xml`
- Make a pull request
+ Or create an issue about what should be included/changed

### Notes
The color scheme is purposedly built for dark-background themes. To use it with a bright one, either make global font `bold` or darken your background a little bit. Alternatively, feel free to contribute a color scheme for bright themes.

File `test.kv` is included only to test highlighting and shouldn't be used as some sort of learning language example.

### License
KV for Notepad++ is under MIT License, more info in LICENSE.txt.
