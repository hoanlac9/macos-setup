# Automated macOS workstation set up

## Features

- Install Homebrew
- Install CLI and GUI packages
- Change system settings
- Install [my dotfiles](https://github.com/khuedoan/dotfiles) and some [macOS specific configuration files](./roles/dotfiles/files)

## Usage

Clone this repository and run the playbook:

```sh
make
```

ansible-playbook -i hosts.ini main.yml --ask-become-pass   