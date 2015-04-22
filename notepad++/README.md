### Syntax:

* If `...\Notepad++\userDefineLang.xml` __exists__ where [Notepad++](https://www.notepad-plus-plus.org/) is installed.
  * Copy and paste the code for [LSL](https://wiki.secondlife.com/wiki/LSL_Portal) from [userDefineLang.xml](userDefineLang.xml).
  * When saving changes to the file make sure the file's encoding is `ANSI/ASCII`!
* If `...\Notepad++\userDefineLang.xml` __does not exist__ where [Notepad++](https://www.notepad-plus-plus.org/) is installed.
  * Open [Notepad++](https://www.notepad-plus-plus.org/) and go to `Language > Define your language > Import` to import a temporary copy of [userDefineLang.xml](userDefineLang.xml) which you can delete when done.
  * Make sure the encoding of the file you are importing is `ANSI/ASCII`!
* Choose the language via `Language > LSL` from the menu. You should should be able to find it at the bottom of the language menu in the section for user defined languages.

![LSL Syntax](_assets/lsl_syntax.png)

### Autocompletion:

* Copy and paste [lsl.xml](plugins/APIs/lsl.xml) to `...\Notepad++\plugins\APIs\lsl.xml` where [Notepad++](https://www.notepad-plus-plus.org/) is installed.
* Make sure the file's encoding is `ANSI/ASCII`!
* Goto `Settings > Preferences > Backup&Autocompletion` and make sure you set `enable auto-completion on each input` to `function completion` and you enable `function parameter hints on input`.

![LSL Autocompletion](_assets/lsl_autocompletion.gif)

### Snippets via FingerText:

Install [FingerText](https://github.com/erinata/FingerText) from the [Notepad++](https://www.notepad-plus-plus.org/) Plugin Manager. Then from the menu go to `Plugins > FingerText > Import Snippets from ftd file` to import the [LSL](https://wiki.secondlife.com/wiki/LSL_Portal) snippets and start working on any file with an `*.lsl`-Extension.

### Code structure:

Add code snippets from [functionList.xml](functionList.xml) to `../Notepad++/functionList.xml` where [Notepad++](https://www.notepad-plus-plus.org/) is installed.

Read more about the [function list in Notepad++](https://www.notepad-plus-plus.org/features/function-list.html) on its homepage.

![LSL Function List](_assets/lsl_function_list.png)

### Code folding:

Having set up the [EOL](https://en.wikipedia.org/wiki/Newline) incorrectly will mess up the code-folding.

Make sure `Edit >> EOL conversion` is set to `Edit >> EOL conversion >> Windows format`.
