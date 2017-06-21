# linuxbook
turning a chromebook into a linuxbook 

documenting some of the journey in the wiki [here](https://github.com/hepler/linuxbook/wiki)

Toshiba Chromebook 2 + GalliumOS

Helpful guides:
- http://www.pants.nu/~jmcminn/toshiba-2015-chromebook-linux.html
- http://nickjanetakis.com/blog/transform-a-toshiba-chromebook-cb35-into-a-linux-development-environment-with-galliumos



### bashrc customization
```
# Set the colors for the prompt
BLUE="\[\e[0;36m\]"
DEFAULT="\[\e[0m\]"
GOLD="\[\e[0;33m\]"
# other gold: \[\e[33;1m\]
YELLOW="\[\e[1;93m\]"

# bolds username yellow, directory path in normal yellow
export PS1="$YELLOW\u$GOLD[\w]$BLUE\$(parse_git_branch) $DEFAULT\$ "
```
