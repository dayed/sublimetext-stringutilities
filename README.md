SublimeText - StringUtilities
===============
StringUtilities is a Sublime Text 3 plugin, which adds to the editor useful string functions like:

* Convert Tabs to Spaces
* Convert Spaces to Tabs
* Convert Chars to Html Entities
* Convert Html Entities to Chars
* Convert Camel Case <-> Underscores
* Convert To Unicode Notation
* Convert From Unicode Notation
* Convert To Base64
* Convert From Base64
* Convert To Hex
* Convert From Hex
* Convert HTML Color From Hex To RGB
* Convert HTML Color From RGB To Hex
* Calculate Selection MD5
* Calculate Selection SHA1
* Convert Unixtime <-> Datetime
* Insert Current Datetime
* Insert Short Password
* Insert Medium Password
* Insert Long Password
* Insert Internal IP Address
* Insert External IP Address


## Installation
The only viable install method right now is via Git:

    git clone https://github.com/LONGMANi/sublimetext-stringutilities "<Sublime Text 3 Packages folder>/StringUtilities"
    cd "StringUtilities"
    git checkout ST3

The "Packages" directory is located at:

* Linux: `~/.config/sublime-text-3/Packages/`
* OS X: `~/Library/Application Support/Sublime Text 3/Packages/`
* Windows: `%APPDATA%/Sublime Text 3/Packages/`

Or enter
```python
sublime.packages_path()
```
into the console (`` Ctrl-` ``).

Usage
------------------

* Right click on editor window (first select text if function is convert type) and select String Utilities menu item.

Todo
------------------

 * Add some missed functions


## Libraries ##

- **dateutil** by Gustavo Niemeyer is used for adding extensions to the standard python 2.3+ datetime module.. **PSF License**

[0]: http://wbond.net/sublime_packages/package_control
