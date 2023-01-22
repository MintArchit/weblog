#hotbindings

## defaults

mode
- **normal**
\               Leader Key
/               Search
Chg Mode to
i               insert
a               append
:				Command

- **cmds**
:messages       List errors
:%s/search_string/replacement_string/ Search & Replace

## vimwiki 

[disabled vimwiki link navigation due to keybinding conflicts](https://github.com/vimwiki/vimwiki/blob/ba84981b5ae54af32e320cd04b583dd7e9fe1c6c/doc/vimwiki.txt#L3311-L3325)

mode:
- **normal**
ctrl+Space      1. transform listitem into task |or
                2. toggle task
Link Navigation 
%%Enter           remove indent
%%Tab				Select next
%%S-Tab			Select previous

- **insert**
:               indent next listitem/task

- **command**
:VimwikiTOC
:VimwikiTable

## NerdTree

m				modify tree structure
r				refresh

