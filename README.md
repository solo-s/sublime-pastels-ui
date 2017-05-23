[![Release | 1.0.0](https://img.shields.io/github/release/e1ectron/sublime-pastels-ui.svg)](https://github.com/e1ectron/sublime-pastels-ui/releases/latest)

# Color Scheme - Pastels UI

A Sublime Text color scheme based on defaults color "Pastels on Dark" and Monokai markup.
Looks perfectly with default Adaptive theme.
Scheme is support for SublimeLinter, Git Gutter and a growing number of plugins.

## Installation

### Using Sublime Package Control
**WARNING**: _Package still waiting for approve, so use [Git](#using-git) or [Manual](#download-manually) installation_
1. Open package control `tools` → `Command Palette` and type `Install Package`
2. Search for `Pastels UI` and hit enter

### Using Git

Alternatively, if you are a git user, you can install the scheme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

	git clone https://github.com/e1ectron/sublime-pastels-ui/ "Color Scheme - Pastels UI"

### Download Manually

* Download the [last release](https://github.com/e1ectron/sublime-pastels-ui/releases/latest)
* Unzip the files
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

Penultimately, open `Preferences` → `Settings - User`. Add the following line:

```json
"color_scheme": "Packages/Theme - Pastels UI/Pastels UI.tmTheme",
```

You can add additional settings, which make the better view.

```json
"theme": "Adaptive.sublime-theme",
"indent_guide_options": [ "draw_normal", "draw_active" ],
"highlight_modified_tabs": true,
"line_padding_bottom": 3,
"line_padding_top": 3,
```

## Screenshots

### JavaScript
![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/js.png)

### CSS
![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/css.png)

### HTML
![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/html.png)

### PHP
![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/php.png)

### Ruby
![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/ruby.png)

### Python
![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/python.png)

### Markdown

![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/markdown.png)

### GitGutter Support

![](https://raw.githubusercontent.com/e1ectron/sublime-pastels-ui/master/screenshots/git-gutter.png)
