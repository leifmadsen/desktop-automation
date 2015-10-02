# desktop-automation
Automation for deploying local configurations for my desktop

## Dependencies
Uses [geerlingguy.dotfiles](http://github.com/geerlingguy/ansible-role-dotfiles) to symlink the files out of my [leifmadsen.dotfiles](http://github.com/leifmadsen/dotfiles) repository. Installs to location determined via `host_vars` file.

## Installation
    $ ansible-playbook -c local site.yml