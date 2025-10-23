# SolarDim VS Code Color Theme (WIP 🚧)

* [What is this](#what-is-this)
* [Showcase](#showcase)
* [Legal](#legal)
* [Changelog](#changelog)
* [Running](#running)
* [Known issues / TODO](#known-issues--todo)

## What is this

## Showcase

## Legal

* [Original readme](./README_ORIGINAL.MD)
* [Original changelog](./CHANGELOG_ORIGINAL.MD)

## Changelog

### 0.1.0

* Changes compared to _Better Solarized Light_ v0.10.9:
  * Base colors: _"Solarized Light colors"_ were swapped for _"SolarDim Colors"_
  * Foreground font color `base00` was darkened (now it's the same as `base01`)
  * `punctuation.definition.list.begin.markdown` (Markdown bullet lists) chnaged from blue to cyan
  * Very very slightly increased contrast on green color

## Running

* `Ctrl` + `F5` to launch extension development instance of VS Code
* Run either `npm run build` after each change or `npm run serve` for "hot reload"

## Known issues / TODO

* 23 elements are referencing `themes.solarized.red`, but that color does not exist (?)

---

[VSCode Color reference](https://code.visualstudio.com/api/references/theme-color)
