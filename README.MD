# SolarDim color theme for VS Code

<img alt="solardim logo" src="https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/solardim_capsule.png" height="125px" />

* [What is this](#what-is-this)
* [Showcase](#showcase)
* [Installation](#installation)
* [Legal](#legal)
* [Running locally](#running-locally)
* [Changelog, TODO, known issues](#changelog-todo-known-issues)

## What is this

SolarDim is an IDE color theme that aims to strike a balance between typical _light_ and _solarized light_ IDE color themes. It is based around the color `#F0EEE6`: the "Light grayish yellow".

The pure white background of light color themes can be too straining on the eyes, while the colors of solarized light color themes can be too warm, especially if you use a software night screen filter or wear computer glasses. If you found out that you can navigate the code better when using a light theme, but the themes mentioned above are too white or yellow for you, you might want to give SolarDim a try.

SolarDim for VS Code is a fork/edit of _vscode-better-solarized_ by _edheltzel_. For more info see the [Legal section](#legal).

## Showcase

Light Modern|SolarDim|Solarized Light
---|---|---
![screenshot of default light vscode](https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/showcase_light.png)|![screenshot of SolarDim vscode](https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/showcase_solardim.png)|![screenshot of default solarized light vscode](https://raw.githubusercontent.com/RDMCz/SolarDim-VSCode/refs/heads/master/_markdown/images/showcase_solarized_light.png)

## Installation

* [VSIX Extension file](https://github.com/RDMCz/SolarDim-VSCode/releases)
* VS Code Marketplace __TBP__

SolarDim is also available for [JetBrains IDEs](https://github.com/RDMCz/SolarDim-JetBrains).

To install VSIX Extension in VS Code:

1. Go to _Extensions_ tab (`Ctrl` + `Shift` + `X`)
2. Click the three dots `...` button located at the top-right corner of _Extensions_ tab (above the extensions search bar)
3. Choose _Install from VSIX..._ option
4. Navigate to downloaded VSIX file and click _Install_

## Legal

This is a fork of [vscode-better-solarized](https://github.com/edheltzel/vscode-better-solarized) by [edheltzel (ginfuru)](https://github.com/edheltzel), who has done most of the heavy lifting. I just changed a few color variables in an existing color theme project with an amazing Nunjucks/Eleventy workflow. You can star the original repo or [buy edheltzel a coffee](https://buymeacoffee.com/edheltzel).

* [Archived edheltzel/vscode-better-solarized README](https://github.com/RDMCz/SolarDim-VSCode/blob/master/_markdown/original/README-ORIGINAL.MD)
* [Archived edheltzel/vscode-better-solarized CHANGELOG](https://github.com/RDMCz/SolarDim-VSCode/blob/master/_markdown/original/CHANGELOG-ORIGINAL.MD)
* [Archived edheltzel/vscode-better-solarized LICENSE](https://github.com/RDMCz/SolarDim-VSCode/blob/master/_markdown/original/LICENSE-ORIGINAL.txt)

Better Solarized then draws inspiration from original [Solarized](https://github.com/altercation/solarized) project by [altercation](https://github.com/altercation).

This project is also licensed under the [MIT license](https://github.com/RDMCz/SolarDim-VSCode/blob/master/LICENSE).

## Running locally

* `Ctrl` + `F5` to launch extension development instance of VS Code
* Run either `npm run build` after each change or `npm run serve` for "hot reload"

&nbsp;

* Run `vsce package` to create a VSIX Extension file

## Changelog, TODO, known issues

* [Changelog](https://github.com/RDMCz/SolarDim-VSCode/blob/master/_markdown/Changelog.MD)

* [TODO, known issues](https://github.com/RDMCz/SolarDim-VSCode/blob/master/_markdown/TODO.MD)

<br>

---

[VSCode Color reference](https://code.visualstudio.com/api/references/theme-color)
