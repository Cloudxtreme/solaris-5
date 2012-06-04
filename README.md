# Installing & Customising Solaris

Welcome to my Solaris Github repository.  This repository is primarily used as a [Wiki for Solaris](wiki) and relevant tweaks I have made to the operating system to make it feel and act more like Ubuntu.

In summary, the files contained in this repository are as follows:

- **inputrc**: Enables better use of the Insert, Delete, Home, End and Page Up/Down keys.
- **layout_24**: Dvorak keyboard layout for the Solaris console window.
- **profile.fots**: This is my default profile that I apply system wide to my Solaris hosts, you're welcome to pick and choose what you like.  Rather than overwriting your /etc/profile with this file, I suggest you include it as follows instead:

  ```bash
  echo ". /etc/profile.fots" >> /etc/profile
  ```