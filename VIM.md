# VIM Cheat Sheet

This is a cheat sheet for intermediate VIM users who are on a quest for a complete mouse-free development life. If you have never heard of VIM,this chearsheet may be of limited use. It's really targetted for folks who are continuously using VIM and building mental muscle memory.

## Setup VIM

* Install [apt-vim](https://github.com/egalpin/apt-vim)
* Plugins
	* bundle
	* delimitMate
	* nerdtree
	* pathogen
	* tagbar
	* vim-closetag
	* [ale](https://github.com/w0rp/ale#installation-with-pathogen)
```
execute pathogen#infect()
filetype plugin indent on
syntax on
```

## Moving
It's a WEB!!

Aspect| Keys| Description|
---|---|---
|character| `h` `j` `k` `l` | moves one character, the arrow keys should work too.
|word| `w` `e` `b`| moves one word at a time forward, forward end of word, back
|line| `0` `$`| move to the beginning column (0) or end.
|page| `H` `M` `L`| High medium low. Within the page move cursor.

* Move 5 words? e.g. `5w`

## Selection
You should be able to select in interesting ways and replace

## Buffers
Open a new tab, or split into multiple buffers

Aspect|Keys|Description
---|---|---
vertical|`:vnew`|Create a new vertical split buffer
horizontal|`:new`|create a new horizontally split 
switch| `ctrl+w+w`|Switch Windows cyclically

# Files
Aspect|Keys|Description
---|---|---
Reload| `:edit!`| it will discard local changes and reload

## References

1. http://vim.wikia.com/wiki/All_the_right_moves
2. https://stackoverflow.com/questions/4478111/vim-how-do-you-open-another-no-name-buffer-like-the-one-on-startup
