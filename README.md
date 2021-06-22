# Configs
This repository is for when I have to export my setup on to a new environment
## Table of content
* [**Terminal**](#terminal)
* [**IDE**](#IDE)

## Terminal
### What I use
* [**Zsh**](zsh.org)
* [**Oh-My-Zsh**](https://ohmyz.sh/)
* [Theme : **Pure**](https://github.com/sindresorhus/pure)
### Installations

#### Oh-My-Zsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
Do that for every user, even root
Once it is done, you are ready to get pure
#### Pure 
Requirements : **npm**
```
npm install --global pure-prompt
```
And then add the following in your .zshrc
```
#.zshrc
ZSH_THEME=""
...
...
autoload -U promptinit; promptinit
zstyle ':prompt:pure:prompt:*' color red
zstyle :prompt:pure:git:branch show yes
zstyle :prompt:pure:git:dirty show yes
prompt pure
```


## IDE
### What I use 
* [**Emacs**](https://www.gnu.org/software/emacs/)
* [**Spacemacs**](https://www.spacemacs.org/)
* [**THEME FORGOTTEN**]()

### Installations
#### Emacs 
It can be installed using apt
#### Spacemacs 
Once emacs installed, run : 
```
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
```
and follow the instructions, they are pretty straight forward

[cool cheatsheet for emacs](https://courses.cs.washington.edu/courses/cse351/16wi/sections/1/Cheatsheet-emacs.pdf)
