# Vagrant + Ansible Instant Web Server (Ubuntu Xenial)

Creates a "localhost" web server using Vagrant and Ansible with Ubuntu 16.04.

Start this up, and you will have an Ubuntu 16.04 VM with Apache 2.4 and PHP 7
running at <http://localhost:8080>, with a doc root of ~/workspace on your
local machine.

## Install dependencies on your Mac

1. install [Xcode from the Mac App Store](https://developer.apple.com/xcode/download/)
2. launch Xcode
3. accept license agreement

Once Xcode is installed, you need to then install the Xcode command-line tools.
In the terminal, type:

```
xcode-select --install
```

This will prompt you to install the Xcode command-line tools. Follow the
prompts.

Once the command-line tools are properly installed, enter the following in the
terminal (it will prompt you for your password one or more times):

```
curl -s https://raw.githubusercontent.com/AaronTraas/osx-setup/master/brew-vagrant-ansible.sh | /bin/bash -s
```

Then change the directory to the directory containing this file, and type:

```
vagrant up
```

In the terminal.
