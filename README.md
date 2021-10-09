# kube-switch
Simple bash script for switching between kubernetes contexts, without too many dependencies. Only requires fzf.

## Installation
`wget -O ~/.config/kube-switch https://raw.githubusercontent.com/tluijken/kube-switch/main/kube-switch`

Place in `~/.zshrc`

`alias ks=~/.config/kube-switch`

### Dependencies
[FZF](https://github.com/junegunn/fzf)

## Usage
kube-switch is interactive. Just run `ks` and interactively select your kubernetes context. 
![image](https://user-images.githubusercontent.com/35781348/136664829-7a0850c6-37a6-4149-9e83-a8bf2935a69c.png)
