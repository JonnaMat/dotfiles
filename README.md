# dotfiles

This repository contains my personal dotfiles, which are configuration files for various programs and tools I use. 
Feel free to explore and utilize these configurations according to your preferences, 
but keep in mind that these settings are tailored to my specific workflow and may require adjustments 
to suit your needs.


## Table of Contents

1. [Introduction](#Introduction)
2. [Usage](#Usage)
3. [bash](#bash)
4. [Feedback](#Feedback)


## Introduction

Dotfiles are hidden configuration files that reside in your home directory (`~`) or config directory (`~/.config`) 
and control the behavior and appearance of various programs in Unix-like operating systems - I use Ubuntu 22.04. 

This repository contains my collection of dotfiles for tools such as:

- Shell configurations (Bash)
- Terminal multiplexers (e.g., Tmux)
- And more...


## Usage

Feel free to browse through the dotfiles and copy any configurations that you find useful. 
However, keep in mind the following:

- **Review Before Use:** Before applying these configurations, 
review the code to understand what each configuration does.
- **Customization:** Modify the configurations to fit your preferences and workflow.
- **Use at Your Own Risk:** These dotfiles are tailored to my specific needs. 
Using them without understanding their implications may cause unexpected behavior. Proceed with caution.


## bash

![bash.png](images%2Fbash.png)

**Note:** I am using `JetBrainsMono Nerd Font` from https://www.nerdfonts.com.

Setup using Symlink from the expected location to this location:

```commandline
ln -s ~/src/dotfiles/bash/.bashrc ~/.bashrc                    
ln -s ~/src/dotfiles/bash/.bash_aliases ~/.bash_aliases
```


## Feedback

Suggestions and improvements are welcome!
