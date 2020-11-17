![screen_grab](./screen_grab.png)
# Environment
ubuntu 18.04 

# Get Started

- git clone --recursive https://github.com/reverie0829/My_tmux.conf.git
- cd My_tmux.conf
- cp tmux.conf ~/.tmux.conf
- tmux source ~/.tmux.conf

# Troubleshooting

**If there is garbled.**

Reason: Check your terminal, and modifying the code under the .tmux.conf .

Example : (oh my zsh)
```
#Enable oh my zsh in tmux
set -g default-command /bin/zsh

#Enable bash in tmux
#set -g default-command /bin/bash
```