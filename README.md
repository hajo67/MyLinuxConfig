My linux configuration files
============================

Git configuration
-----------------

Setting user email and name:

```bash
git config --global user.email "MAILADDRESS"
git config --global user.name "USERNAME"
```

Setting the editor - you don't want emacs ...:

```bash
git config --global core.editor "nvim-qt"
```

You once need to activate, that credentials get saved locally:

```bash
git config --global credential.helper store
```

Credentials will then be saved in ~/.git-credentials

Preconditions
-------------

These packages need to be installed:

* xbindkeys
* xdotool
* xcape
* neovim & neovim-qt

File/Folder overview
--------------------

* .bashrc -> My .bashrc file
* .inputrc -> My .inputrc file
* .xbindkeysrc -> My xbindkeys configuration file
* .config/autostart -> Autostart files
