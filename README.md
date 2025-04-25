This is based on [ThePrimeagen's version of Dvorak](https://github.com/ThePrimeagen/keyboards), focused on better supporting macOS.

## Install
- Download the bundle from this repo
- Move it to `~/Library/Keyboard Layouts/`
- Might need to restart for it to be detected
- Both layouts should show up as an input source

## Why are there 2 versions?
There's 2 versions depending on what you want out of the layout.

The **dry** version contains only two layers: the regular keys and shifted keys. There's none of the fancy macOS stuff in it.

The **standard** version uses the built-in macOS Dvorak as a base, with the new layout added onto it. This gives you all the macOS features such as:
- The symbols on the option key layer
- Correct handling of shifted keys with caps lock
  - One exception to this rule is the dash key. When in caps lock it will turn into underscore to make typing SNAKE_CASE faster
- All the [text manipulation features](https://support.apple.com/en-us/102650) on the control layer, so Ctrl-h still functions as backspace and so on
