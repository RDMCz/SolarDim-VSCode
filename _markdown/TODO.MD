# SolarDim color theme for VS Code

[← Back to root](https://github.com/RDMCz/SolarDim-VSCode)

## TODO

I use VS Code these days mainly for writing Markdown, and I'm happy with how Markdown currently looks with this color theme. For actual programming, however, I prefer products from JetBrains, for which I also released SolarDim. This extension inherits from _vscode-better-solarized_ by _edheltzel_, while the JetBrains plugin inherits from _solarized_ by _espositocode_. The color palette of these two color themes is the same, but they differ in the specific color selection for the keywords of the given programming languages. I would like to review the colors for languages I use and I would also like them to be the same in both versions. I prefer some color decisions from one theme and some from the other (whether these were intentional or implied), so deciding how SolarDim should approach colors for programming languages isn't straightforward.

* [ ] Colors of things other than programming language keywords
  * [ ] Autocomplete menu – highlighted option should have darker font, not lighter (highlight background is orange)
* [ ] Python
  * [ ] Treat docstrings same as comments instead of treating them as string
  * [ ] Named parameters `f(par1=val1)`: make `par1` cyan instead of red; make equal sign black?
  * [ ] Calling functions should be blue, but is sometimes black (maybe VS Code cannot detect them properly? maybe it will get better with Pytohn plugin?)
  * [ ] Function definition: parameter names: make them dark instead of red
  * [ ] Valid string escape sequence (like `\n`): make it magenta
  * [ ] Make quotes around green string also green instead of cyan ?
  * [ ] Comparisons: `and`, `or`, `not`, ... – violet; `==`, ... – black
  * [ ] Data types: `str`, `int`, `bytes` – make em blue instead of yellow
  * [ ] PyCharm does not support special styling for `True`/`False`/`None` – decide if I prefer red or make it the same as PyCharm
* [ ] Rust
* [ ] Go
* [ ] JavaScript
* [ ] ...
* [x] Markdown
  * [ ] `~~striked text~~` has no special effect, maybe add some?
* [ ] JSON
* [ ] XML, HTML
* [ ] CSS

## Known issues

* 23 elements are referencing `themes.solarized.red`, but that color does not exist (?)
