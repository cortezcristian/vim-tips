vim-tips
========

Vim Tips


## Tabs

Reopen closed tab ([Undo Close Tab in Vim](http://stackoverflow.com/a/22671022/467034))
```
:tabnew#
```

## Indent

Indent HTML file ([How do I tidy up an HTML file's indentation in VI?](http://stackoverflow.com/a/14114909/467034))

```
:filetype indent on
:set filetype=html           # abbrev -  :set ft=html
:set smartindent             # abbrev -  :set si
```

Shortcut: `gg =G`
