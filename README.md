# twupd
Just a simple OpenSUSE Tumbleweed update script of mine.

## Installation

Execute this command to install the script in your HOME folder :

```
mkdir -p $HOME/bin && echo 'export PATH="$HOME/bin:$PATH"' >> $(case $SHELL in */bash) echo "$HOME/.bashrc";; */zsh) echo "$HOME/.zshrc";; */fish) echo "$HOME/.config/fish/config.fish";; *) echo "$HOME/.profile";; esac) && curl -L https://raw.githubusercontent.com/Rawleenc/twupd/main/twupd -o $HOME/bin/twupd && chmod +x $HOME/bin/twupd
```

## Usage

Just execute the script without any options or arguments :

```
twupd
```
