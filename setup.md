---
layout: page
title: Setup
permalink: /setup/
---
Your installation for `Git` will vary depending on your operating system.

- Mac OSX - `git` is already installed on your machine.
    - If you have an older OSX, you may still need to download `git`. [Detailed installation instructions](https://swcarpentry.github.io/workshop-template/#git)
- Linux - `git` is already installed on your machine.
- Windows - you will need to install the components:
    - [Installation video](https://www.youtube.com/watch?v=339AEqk9c-8)


1. Download the Git for Windows [installer](https://git-for-windows.github.io/)
1. Run the installer and follow the steps bellow:
    1. Click on "Next".
    1. Click on "Next".
    1. **Keep "Use Git from the Windows Command Prompt" selected and click on "Next".** If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
    1. Click on "Next".
    1. **Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".**
    1. **Keep "Use Windows' default console window" selected and click on "Next".**
    1. Click on "Install".
    1. Click on "Finish".

1. If your "HOME" environment variable is not set (or you don't know what this is):
Open command prompt (Open Start Menu then type `cmd` and press [Enter])
Type the following line into the command prompt window exactly as shown:

`setx HOME "%USERPROFILE%"`

Press [Enter], you should see `SUCCESS: Specified value was saved`.
Quit command prompt by typing `exit` then pressing [Enter]
