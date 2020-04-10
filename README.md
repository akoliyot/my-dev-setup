# Dev Setup
This list is to help me with syncing up my development preferences on my work and personal laptops.
# Toolbox
Editor  
**[VSCode](https://code.visualstudio.com/)**  

Font  
**[FiraCode](https://github.com/tonsky/FiraCode)**

Terminal  
**[iTerm2](https://www.iterm2.com/)**  ([Settings](/appSettings/Aswin's%20Terminal.json) • [Theme](https://github.com/taniarascia/new-moon/tree/master/iterm2))

Window Manager  
**[Rectangle](https://rectangleapp.com/)** ([Settings](/appSettings/Container.plist))

# Settings


## User Environment (.zshrc)
**Adding separators between commands:** 
```
#
# Setup for adding separators between commands on the terminal.
#
setopt promptsubst
PS1=$'${(r:$COLUMNS::_:)}'$PS1
```