# Ansible Role: Vim Vundle

Installs [Vundle.vim][vundle].

## Requirements

- curl
- git
- vim

## Role Variables

Available variables with example values are listed below, for default values see
[`defaults/main.yml`](defaults/main.yml)):

    vim_vundle_repo: https://github.com/VundleVim/Vundle.vim.git
    vim_vundle_local_destination: ~/.vim/bundle/Vundle.vim

## Dependencies


## Example Playbook

    - hosts: localhost
      roles:
         - { role: lwalley.vim-vundle }

## License

BSD

[vundle]: https://github.com/VundleVim/Vundle.vim
