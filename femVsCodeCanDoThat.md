# FEM - VS Code Can Do That

## Kill Process on specific port

Mac/Linux:

```
lsof -i tcp:3000
Find the ID of the process
kill <process id>
```

## Shortcuts

Open/Close Sidebar

```
CMD + B
```

File Switcher

```
CMD + P
```

Show Terminal

```
CMD + ~
```

Show Panel

```
CMD + J
```

Show Settings

```
CMD + ,
```

## Themes

Changes themes

```
CMD + SHIFT + P
Preferences:Color Themese
```

Notable Themes

- synthwave
- cobalt
- dracula
- outrun

Icon Themes

- challice
- pug

## Fonts

1. download font
2. tell vscode to use it

- cmd + ,
- FiraCode

3. Enable font ligatures if that is your preference

## Settings.json

- json file that is behind the settings ui

Move Sidebar position

```
cmd + shift + p
toggle side bar position
```

Change presentation of settings

- json offers ability to see all settings at the same time

```
cmd + ,
workbench > settings > editor
change to  'ui' to 'json'
```

Create shortcut to have Settings UI and Settings JSON

```
cmd + shift + p
open keyboard shortcuts
search settings ui
set keyboard shortcut to cmd + alt + ,
```

Turn off breadcrumbs
in settings.json

```
breadcrumbs.enabled: false
```

Toggle Activity Bar

```
cmd + shift + p
toggle activty bar
```

Create toggle activity bar shortcut

```
cmd + shift + p
keyboard shortcuts
ctrl + cmd + b
```

Peacock Extension

- allows theming of different instances of vscode
- useful if you have multiple instances of vscode open so you can differentiate between the two

Bracket Pair Colorizer

- changes the color of nested brackets so its easier to match
- only good for dark themes

## Emmet for Html + Css

Build boilerplate html page

```
! + tab
```

- tab to select the editable items like description
- use parens to group adjacent elements and then hit ctrl+spacebar to bring back emmet to expand

Format Document

- use prettier extension to format document

```
cmd + shift + p
format document
```

Toggle format on save

```
cmd + alt + ,
format on save
```

Bulma Css Framework

-

Emmet Balance outward

- grabs all code within current tag

```
ctrl + shift + up
or
cmd + shift + p
Emmet balance outward
```

Emmet Balance inward keyboard shortcut

- grabs all code within the next child tag

```
ctrl + shift + down
or
cmd + shift + p
Emmet balance inward
```

Emmet Wrap With Abbreviation

```
cmd + shift + p
Emmet Wrap with Abbreviation
or

```

Emmet Update Tag

- update/change tag when cursor on the line with the tag

```
cmd + shift + p
emmet update tag
```

Emmet Update Image Size

- populates the image tag with the width/height dimensions automatically
- works for both html/css

```
cmd + shift + p
emmet update image size
```
