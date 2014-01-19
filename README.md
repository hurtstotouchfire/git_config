Instructions
=========

This assumes you've done nothing to set up git beyond registering a Github account and getting added to the org, and that you are running Mac OS or a Linux variant with a bash terminal.


Install git
------------

Mac: I recommend using [homebrew](http://brew.sh/)
```
brew install git
```
Linux: your package manager of choice, in my case apt
```
sudo apt-get install git
```

Clone this repo
----------------
I keep all of my git repos in one directory: `~/src`, but you can put this wherever you want. Since you should keep it and pull occasionally for bug fixes and updates, you might want to just clone it right in your home directory. Cloning will make a subdirectory and pull all the contents of this repo into it.

```
cd ~/
git clone git@github.com:CRC-BU/git_config.git
```
Add prompt configuration to your bashrc
---------------------------------------
Since nearly every machine has one already, I assumed that appending would be the easiest option for everyone. If you don't have a file at `~/.bashrc`, you can just copy `append_to_bashrc` into your home directory. Just add `#!/bin/bash` on the first line of the file.

After saving this, you can open a new terminal, or re-source your bashrc (run: `. ~/.bashrc`) to see the effects. This wil color your prompt, and if you cd into the git_config directory we just cloned, you should see the branch "master" listed in the prompt.

Running git setup script
------------------------
