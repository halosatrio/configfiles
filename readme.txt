log 2021 03 16 - 15.05

OS: ubuntu 20.04
shell: bash, fish-shell
default shell: fish-shell 3.10

fish-shell config:
	- prompt: shasimi prompt

terminal: gnome terminal, terminator

terminator-config:
	- font: mesloLGS NF Regular, 10
	- color-palette: dracula
	
apps instaled:
	- vscode
	- insomnia
	- terminator
	- firefox
	- chrome
	- vlc
	- htop
	- neofetch
	- node 14.16.0
	- git 2.25.1
	- yarn 1.22.10
	
vscode extensions:
	- bracket pair colorizer 2
	- ES7 Rect/Redux/GraphQL/React-Native snippets
	- Git Graph
	- GitLens
	- Prettier
	- React Native Tools
	- Tailwind CSS IntelliSense
	- vscode-icons
	- one dark pro
	
Fonts installed:
	- Fira Code
	- mesloLGS NF
	
git aliases:
alias.alias config --get-regexp alias.*
alias.st status
alias.a add .
alias.ci commit -m
alias.co checkout
alias.br branch
alias.hist log --pretty=format:"%h %ad | %s%d [%an]" --graph --date=short
alias.last log -1 HEAD
alias.log log --full-history
alias.lol log --all --oneline --graph --decorate
