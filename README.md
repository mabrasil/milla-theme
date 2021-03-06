<img src="https://raw.githubusercontent.com/mabrasil/milla-theme/master/img/milla-logo.png" align="center">

Milla is just a simple (and alternative) dark theme for SublimeText, Textmate and other 
text editors that uses a flat color palette.

## Table of contents

* [Using](#using)
  * [Sublime Text](#sublime-text)
  * [Atom](#atom)
  * [TextMate](#textmate)
  * [Vim](#vim)
* [Color Palette](#color-palette)
* [License](#license)
* [Versioning](#versioning)
* [TODOs](#todos)

##Using

### Sublime Text 

#### Install using Git

You can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

```sh
$ git clone https://github.com/mabrasil/milla-theme.git "Milla Color Scheme"
```

#### Download Manually

1. Download the files using the [GitHub .zip download](https://github.com/mabrasil/milla-theme/archive/master.zip) option
2. Unzip the files and rename the folder to `Milla Color Scheme`
3. Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
4. Copy the folder into your Sublime Text `Packages` directory

#### Activating the theme

Go to `Preferences -> Color Scheme -> User` and select the `Milla Color Scheme`.

### Atom

#### Install using Git

You can install the theme and keep up to date by cloning the repo directly into your `~/.atom/packages` directory.

```sh
$ git clone https://github.com/mabrasil/milla-theme.git ~/.atom/packages/milla-theme
```

#### Download Manually

1. Download the files using the [GitHub .zip download](https://github.com/mabrasil/milla-theme/archive/master.zip) option
2. Unzip the files and rename the folder to `milla-theme`
3. Move the `milla-theme` folder to `~/.atom/packages`

#### Activating the theme

Go to `Atom -> Preferences...`, select the `Themes` tab on the left side and choose `Milla` in the `Syntax Theme` dropdown menu.

### TextMate

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```sh
$ git clone https://github.com/mabrasil/milla-theme.git "Milla Color Scheme"
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/mabrasil/milla-theme/archive/master.zip) option and unzip them.

#### Activating theme

Just open the `Milla.tmTheme` file using TextMate app.

### Vim

#### Install using use Vim + Pathogen

```sh
$ cd ~/.vim
$ git submodule add git@github.com:mabrasil/milla-theme.git bundle/milla-theme
```

#### Download Manually

1. Download the files using the [GitHub .zip download](https://github.com/mabrasil/milla-theme/archive/master.zip) option
2. Unzip the files and move the `vim/colors/milla.vim` file into `~/.vim/colors`
3. Add the following lines into your vimrc file:

```
syntax on
color Milla
```
## Color Palette

Palette                  | Foregound | Background           
---                      | ---       | ---   
Background               | `#fff`    | `#282a36` 
Foreground               | `#ecf0f1` | `#fff`
Comment                  | `#7280a3` | `#fff` 
String                   | `#f4d03f` | `#fff`
Built-in Coonstant       | `#9b59b6` | `#fff` 
User-defined Coonstant   | `#9b59b6` | `#fff`
Keyword                  | `#db0a5b` | `#fff` 
Storage                  | `#db0a5b` | `#fff`
Storage Type             | `#75b9e7` | `#fff` 
Class Name               | `#16a085` | `#fff` 
Inherited Class          | `#16a085` | `#fff` 
Function Name            | `#27ae4c` | `#fff`
Function Argument        | `#d34a00` | `#fff`   
Tag Name                 | `#db0a5b` | `#fff` 
Tag Atribute             | `#87d37c` | `#fff` 
Library Function         | `#3498db` | `#fff`
Library Constant         | `#3498db` | `#fff` 
Library Clas/Type        | `#3498db` | `#fff`
Library Variable         | `#fff`    | `#fff` 
Invalid                  | `#fff`    | `#c0392b` 
Invalid Deprecated       | `#fff`    | `#96281b` 

##License

Milla is distributed under the MIT License, available in this repository.

##Versioning

It is intended to maintain this project under the [Semantic Versioning] (http://semver.org/) guidelines. Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

##TODOs

- [ ] Add more scopes to existing themes
- [ ] Add Screenshots to README.md
- [ ] Add the existing versions to their text editors' respectives package managers.
- [ ] Make it available for other editors (Brackets, Xcode etc.) and Terminal.
