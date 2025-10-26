# SolarDim VS Code Color Theme

<img alt="solardim logo" src="https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/solardim_capsule.png" height="125px" />

* [What is this](#what-is-this)
* [Showcase](#showcase)
* [Installation](#installation)
* [Legal](#legal)
* [Changelog](#changelog)
* [Running locally](#running-locally)
* [Known issues / TODO](#known-issues--todo)

## What is this

SolarDim is an IDE color theme that aims to strike a balance between typical _light_ and _solarized light_ IDE color themes. It is based around the color `#f0EEE6`: the "Light grayish yellow".

The pure white background of light color themes can be too straining on the eyes, while the colors of solarized light color themes can be too warm, especially if you use a software night screen filter or wear computer glasses. If you found out that you can navigate the code better when using a light theme, but the themes mentioned above are too white or yellow for you, you might want to give SolarDim a try.

SolarDim for VS Code is a fork/edit of _vscode-better-solarized_ by _edheltzel_. For more info see the [Legal section](#legal).

## Showcase

Light Modern|SolarDim|Solarized Light
---|---|---
![screenshot of default light vscode](https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/showcase_light.png)|![screenshot of SolarDim vscode](https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/showcase_solardim.png)|![screenshot of default solarized light vscode](https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/showcase_solarized_light.png)

## Installation

* [VSIX Extension file](https://github.com/RDMCz/SolarDim-VSCode/releases)
* VS Code Marketplace __TBP__

## Legal

This is a fork of [vscode-better-solarized](https://github.com/edheltzel/vscode-better-solarized) by [edheltzel (ginfuru)](https://github.com/edheltzel), who has done most of the heavy lifting. I just changed a few color variables in an existing color theme project with an amazing Nunjucks/Eleventy workflow. You can star the original repo or [buy edheltzel a coffee](https://buymeacoffee.com/edheltzel).

* [Archived edheltzel/vscode-better-solarized README](./_markdown/README-ORIGINAL.MD)
* [Archived edheltzel/vscode-better-solarized CHANGELOG](./_markdown/CHANGELOG-ORIGINAL.MD)
* [Archived edheltzel/vscode-better-solarized LICENSE](./_markdown/LICENSE-ORIGINAL.txt)

This project is also licensed under the [MIT license](./LICENSE).

## Changelog

### 0.0.1

* Changes compared to _Better Solarized Light_ v0.10.9:
  * Base colors: _"Solarized Light colors"_ were swapped for _"SolarDim Colors"_
  * `punctuation.definition.list.begin.markdown` (Markdown bullet lists) changed from blue to cyan

## Running locally

* `Ctrl` + `F5` to launch extension development instance of VS Code
* Run either `npm run build` after each change or `npm run serve` for "hot reload"

&nbsp;

* `vsce package` to create a VSIX Extension file

## Known issues / TODO

* 23 elements are referencing `themes.solarized.red`, but that color does not exist (?)

<br>

---

[VSCode Color reference](https://code.visualstudio.com/api/references/theme-color)
