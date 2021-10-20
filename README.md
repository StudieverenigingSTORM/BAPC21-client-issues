# BAPC21-client-issues

The purpose of this repo is to only collect issues with the bapc-2021.ova image
 - the image can be downloaded here:
   - https://2021.bapc.eu/bapc-2021.ova
 - in virtualbox you can load the .ova by selecting _File -> Import Applicance_
 - this file can also be loaded in other VM managers, but this has not been tested by us
 - if you find a problem, please create a new github issue in this repository

## Basic Information

### Account Login
 - the _test_session_ and _bapc_2021_ accounts in the bapc-2021.ova image require no password (and are identically configured)
 - you cannot access the _admin_ account, unless you are a terrific password guesser...
 - you do not get sudo rights

### Internet Access
 - is allowed in the bapc-2021.ova image, but will not be allowed during the contest itself (i.e. you can install your favorite extensions on your favorite IDE's here, but you will not be able to do this during the actual contest)

## Installed Software

### Editors
 - vim
 - emacs
 - geany
 - kate
 - kwrite
 - sublime text

### IDE's and Extensions
 - vscode
   - ms-python.python
   - ms-vscode.cpptools
   - redhat.java
   - coenraads.bracket-pair-colorizer
 - intellij (community edition)
 - pycharm (community edition)
 - clion
 - codeblocks
 - mono-complete
 - kdevelop

## Compiling and Running Code
 - there are certain commands you can use to compile your code in the same way that DOMjudge will judge your submissions
 - you can find these commands by running the following command in a terminal:
   - cat ~/.bash_aliases
