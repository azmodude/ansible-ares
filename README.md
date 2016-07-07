# ansible-ares

My main work laptop configuration, currently for Fedora 24.

For the corresponding dotfile repository please see [my dotfiles](http://github.com/azmodude/dotfiles).

## Prerequisites

    sudo dnf -y install ansible libselinux-python python2-dnf

## Usage
    
    ansible-playbook -K -i inventory playbook.yml
