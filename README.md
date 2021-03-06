# Get Started

Repository contains ansible playbook that is use to install basic softwares on new Linux OS.

## List of softwares

- vim
- xclip
- Powerline
- vim-powerline
- Google Chrome stable

## Prequisites

To run ansible playbook, system should have ready with **python 2** and **ansible**

Execute these commands(for fedora):

```
$ sudo dnf install python2 python-pip libselinux-python

$ pip install -U ansible
```

Check ansible version by executing,

```
$ ansible --version
```

## How to run playbook

This playbook is designed to install softwares on local machine. We can also run this playbook on remote machines with some changes. 

To start installing softwares on your system, execute playbook as,

```
$ ansible-pull -U https://github.com/akshay196/get-started -i hosts --ask-become-pass install.yml
```

Type your password if ask.

## Licensing

Code is licensed under GNU General Public license v3.0. See [LICENSE](https://github.com/akshay196/get-started/blob/master/LICENSE) for full license.

## Acknowledgment

This is inspired by [get_started_with_fedora](https://github.com/khomesh24/get_started_with_fedora/) by @khomesh24
