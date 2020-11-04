# ZSH Configuration.

This is a really simple ZSH config I use as a starting point for a nice environment for systems I use.

You might want to look at a more full-featured thing like oh-my-zsh or prezto over using this.

I'd suggest forking this repo rather than using it directly if you do want to use it and customising to your liking, but this isn't really intended for other people to use.

Install process:

  - Install `zsh`, e.g: `sudo apt install zsh zsh-doc`
  - Grab the repository: `git clone --recursive https://github.com/Lattyware/zsh.git "${XDG_CONFIG_HOME:-${HOME}/.config}/zsh"`
  - Link the main script: `ln -s "${XDG_CONFIG_HOME:-${HOME}/.config}/zsh/rc" "${HOME}/.zshrc"`
  - Set your user's default shell to zsh: `sudo usermod --shell "$(which zsh)" "$(whoami)"`
