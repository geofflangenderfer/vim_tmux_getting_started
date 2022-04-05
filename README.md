# Install
```
# append our vim related configs to our existing config files
cat .zshrc >> ~/.zshrc
cat .tmux.conf >> ~/.tmux.conf
```
## tmux
```
# mac
brew install tmux
# ubuntu
sudo apt install tmux
# amazon linux
sudo yum install tmux
```

# tmux instructions

- navigation mode (move about within terminal output window)
	- ctrl + b + [
- copy (must be inside navigation mode)
	- shift + v + enter
	- spacebar + select desired text + enter
- paste (navigation mode not necessary)
	- ctrl + b + ]
