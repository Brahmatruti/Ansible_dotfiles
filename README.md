# dotfiles

This repo contains the configuration to setup my machines. This is using [Chezmoi](https://chezmoi.io), the dotfile manager to setup the install.

This automated setup is currently only configured for Fedora machines.

## How to run

```shell

sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply https://github.com/$GITHUB_USERNAME/Ansible_dotfiles.git
