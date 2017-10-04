# TMUXINATOR

It is used for creation and management of tmux sessions.

### Requirements
- tmux `brew install tmux`
- reattach-to-user-namespac `brew install reattach-to-user-namespace`
- ruby

### Instalation
- `gem install tmuxinator`
- make sure you have the correct completion file (this repo contains the bash version). Visit 
https://github.com/tmuxinator/tmuxinator/tree/master/completion and download the appropriate completion file.
- create a symlink from `.tmux.conf` found in this repo to `~/.tmux.conf`

### Configurations
- in your `.bash_profile` file add the folowing configuration
```
# tmuxinator
export EDITOR='your editor of choice'
export TMUXINATOR_CONFIG='path to save your configuration files'

source PATH_TO_TMUXINATOR_BASH
```

### Usage
- create new project `tmuxinator new [project]`
- edit a project `tmuxinator edit [project]`
- start a session `tmuxinator start [project]`

# TMUX
