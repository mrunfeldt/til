# Run JupyterHub

```bash
# change to root
sudo su -
# start tmux (or reattach w/ tmux attach)
tmux

# source conda environment
source activate py3

# Only use this if you have security another way.
jupyterhub --no-ssl

# Detach from tmux
^b d
```
