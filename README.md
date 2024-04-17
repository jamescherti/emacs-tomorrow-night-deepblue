# tomorrow-night-deepblue-theme.el (Emacs theme)

The **Tomorrow Night Deepblue Emacs theme** is a beautiful deep blue variant of the Tomorrow Night theme, which is renowned for its elegant color palette that is pleasing to the eyes.

The **Tomorrow Night Deepblue theme** features a deep blue background color that creates a calming atmosphere. The theme is also a great choice for those who miss the blue themes that were trendy a few years ago.

## Table of Contents

- [Screenshot](#screenshot)
- [Installation](#installation)
- [Authors](#authors)
- [Links](#links)

## Screenshot

The theme was actually inspired by classic DOS text editors such as QuickBASIC, RHIDE, and Turbo Pascal, which featured blue backgrounds by default. There's something special about the early days of programming and the tools we used that brings back fond memories.

![](https://raw.githubusercontent.com/jamescherti/emacs-tomorrow-night-deepblue-theme/master/.screenshot.png)

# Installation

Open a terminal and execute the following commands. These commands will create a directory for themes if it doesn't already exist, navigate into it, and then clone the theme files from the official Git repository:
```
mkdir -p ~/.emacs.d/themes
cd ~/.emacs.d/themes
git clone https://github.com/jamescherti/emacs-tomorrow-night-deepblue-theme
```

After downloading the theme, you need to modify your Emacs configuration file to include this theme. Open or create the `~/.emacs.d/init.el` directory and add the following lines of code:
```
;; Add the theme's directory to the path where Emacs searches for loading files
;; and require the Tomorrow Night Deepblue theme
(add-to-list 'load-path "~/.emacs.d/themes/emacs-tomorrow-night-deepblue-theme")
(require 'tomorrow-night-deepblue-theme)

;; Disable all other themes
(mapc #'disable-theme custom-enabled-themes)

;; Load the Tomorrow Night Deepblue theme
(load-theme 'tomorrow-night-deepblue)
```

## Authors

Tomorrow Night Deepblue theme maintainer: [James Cherti](https://www.jamescherti.com/)

The tomorrow-night-deepblue theme is based on Tomorrow Night Blue by Chris Kempson, Steve Purcell, and Donald Curtis.

## Links
- [GitHub: Tomorrow Night Deepblue Emacs theme](https://github.com/jamescherti/emacs-tomorrow-night-deepblue-theme)
- [Announcement in James Cherti's website about this theme](https://www.jamescherti.com/emacs-tomorrow-night-deepblue-theme-a-refreshing-color-scheme-with-a-deep-blue-background/)
- [Vim version: Tomorrow Night Deepblue for the Vim editor]( https://github.com/jamescherti/vim-tomorrow-night-deepblue)
