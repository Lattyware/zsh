# ZSH Configuration.

Install process:

  - Install `zsh`, e.g: `sudo apt install zsh zsh-doc`
  - Grab the repository: `git clone --recursive git@github.com:Lattyware/zsh.git "${XDG_CONFIG_HOME:-${HOME}/.config}/zsh"`
  - Link the main script: `ln -s "${XDG_CONFIG_HOME:-${HOME}/.config}/zsh/rc" "${HOME}/.zshrc"`
  - Set your user's default shell to zsh: `sudo usermod --shell "$(which zsh)" "$(whoami)"`
