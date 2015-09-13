tmux-sessions
=============

Collection of tmux scripts to launch commonly configured sessions / window configurations.

### Requirements

* tmux

# Install

## Clone repo to ~/local
```
cd ~/local
git clone https://github.com/scmorrison/tmux-sessions.git
```

## Add scripts directory to path
```
# Add to ~/.bash_profile
export PATH=$PATH:$HOME/local/tmux-sessions/scripts
```

# Scripts

* [tmux-command-center] - Start a three window session (system, tools, misc) using PWD as the name of the session.
* [tmux-web-dev] - Start a three window session (server, vim, test) using PWD as the name of the session.
* [tmux-music] - Start a two window session (pianobar, mocp) using `music` as the name of the session. Create an ssh tunnel before launching `pianobar`. Launch `mocp` in the mocp window.

# License

GPLv3

[tmux-command-center]: scripts/tmux-command-center
[tmux-web-dev]: scripts/tmux-web-dev
[tmux-music]: scripts/tmux-music
