# Typora Side-by-side

A CSS theme extension for [Typora](https://typora.io/) that enables side-by-side view for certain blocks. It is built to be used on top of whatever theme your are already using (see [Installation](#installation)).

Pull requests are welcome here 👍 if you have any ideas that would make this theme extension better.

I made this because I thought it was lacking in Typora and it was mentioned a lot in [typora-issues](https://github.com/typora/typora-issues) ([#70](https://github.com/typora/typora-issues/issues/70), [#4215](https://github.com/typora/typora-issues/issues/4215), [#3453](https://github.com/typora/typora-issues/issues/3453), [#3709](https://github.com/typora/typora-issues/issues/3709), [#4154](https://github.com/typora/typora-issues/issues/4154), ...)

## Screenshots

no screenshots for the moment

## Installation

You can refer to [Typora custom CSS](https://support.typora.io/Add-Custom-CSS/) documentation page in order to add this custom css to your editor.
Everything that you need is in the _base.user.css_ file.

Name the css file:

* **base.user.css** if you want it to be applied by default on top of all your themes
* **\<theme-name>.user.css** if you want it to be applied only on top of a particular theme

⚠️ If this file already exists, append the content of the _base.user.css_ at the end of it!

## Currently supported blocks

- Math blocks (\$\$)

## Themes compatibility

Compatibility tested with following Typora themes:

- GitHub Night
- GitHub
- Hivacruz
- Newsprint
- Night
- Nord
- Onedark
- Panda (built on top of this theme initially)
- Pixyll
- Quartz Milky
- Whitey
- Xydark
- Xydark focus
- Xylight

Please send me a message if you see that my extension works with a theme that is not present above so that I can add it to the list.
