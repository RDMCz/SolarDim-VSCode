# SolarDim color theme for VS Code

[← Back to root](https://github.com/RDMCz/SolarDim-VSCode)

## Changelog

### 0.1.1

* Introduce new _darkCyan_ color (#43736F), which is now used for _keyword.operator_

### 0.1.0

* Global:
  * Project cleanup
  * Change _Function Argument_ from orange to teal
  * Change cyan operators to black, except tags; also make quotes around strings green
  * Generic function call is now blue (was not set before)
  * Change constant character escape from orange to magenta
  * Change built-in type from yellow to blue
* Markdown:
  * Inline code now has different color than normal text
* Python:
  * Docstring now has the same color as a comment (gray) instead of a string (green)
  * Logical operators (and/or/not) are now violet
* Misc:
  * More dark gray for some RainbowCSV & Nunjucks selectors
  * C#: Do not highlight html tags inside `<summary>` comments; similiar treatment to Java

### 0.0.2

* Markdown: `~~striked text~~` is now visibly striked in editor
* The text of highlighted items in lists (such as menus and autocomplete suggestions) is now black for better contrast

### 0.0.1

* Initial release
* Changes compared to _Better Solarized Light_ v0.10.9:
  * Base colors: _"Solarized Light colors"_ were swapped for _"SolarDim Colors"_
  * `punctuation.definition.list.begin.markdown` (Markdown bullet lists) changed from blue to cyan
