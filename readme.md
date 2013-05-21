# Notepad++ Markdown Highlighting

## Default Branch

+ Updated to use default colour style.
+ Basic syntax for html open bracket will highlight `<`.
+ Included pipe `|` keyword for tables syntax.

## Colors

This works for the 'Default' colour scheme.

## Style Guide

Because of limits of the generic Notepad++ user defined language lexer, highlighting is partial and a little buggy. But you can still get a lot out of it if you follow some simple style rules:

  + Use the `#` syntax for headers, not underlines.
  + Remember `*`, `_`, and `>` only highlight the first word they've marked down.
  + Use `+` for lists, or change it in the dialog to dashes. Asterisks will conflict with emphasis highlighting.
  + Horizontal rules should be 3 to 13 dashes, no spaces.
  + Nothing works if you start or end it inside a word.
  + Remember there's no highlighting for indentation/\<pre\> tags.
  
## How to use

  1. Open `\[user]\AppData\Roaming\Notepad++`
  2. Replace your `userDefineLang.xml` with the one in this repo, or add the contents of this `userDefineLang.xml` to the end of your current one.
  3. Restart Notepad++.
  4. Markdown highlighting will now automatically apply to `.mkdn`, `.mkd`, and `.md` files, or you can manually select it from the bottom of the "Language" menu.
  
## Extra nerdity

  If you like the way this highlighter looks so much you want to read everything in it, there's a css file that lets you do just that.