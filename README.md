# tmux-config
tmux configuration designed to seamlessly integrate with my [NVChad configuration](https://github.com/anormalrobot/nvchad-config). This configuration based on the YouTube video of the  Gigachad [Dreams of Code](https://www.youtube.com/@dreamsofcode). If you want to use this configuration please subscribe [his channel](https://www.youtube.com/@dreamsofcode) and like the [tmux](https://www.youtube.com/watch?v=DzNmUNvnB04) configuration video.
## Installation
1. Install tmux:
```bash
$ sudo apt install tmux
```
2. Install tpm:
```bash
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
2. Install tmux configuration:
```bash
$ git clone https://github.com/anormalrobot/tmux-config.git ~/.config/tmux/
```
- Open a new tmux session then press `<prefix-key>+I` to install plugins. The prefix key is `C-b` by default, I remapped prefix key to `C-Space` to be like in neovim. 
- Restart tmux session or source with `tmux source ~/.config/tmux/tmux.conf`.
