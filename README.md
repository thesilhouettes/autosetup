# Autosetup

I tried to write a shell script that setups and configures a freshly installed
Arch Linux system (it uses `pacman` and `yay`). It is basically different
commands grouped inside shell functions.

**Warning: It is not tested, use it with care.**

## Customization

Provide `DOTFILES_URL` before the script invocation, so it uses your
repository. Also, provide `BARE_REPO_DIR` for the bare repository locations. I
may add other methods later.

Change `aurpkgs.txt` and `mainpkgs.txt` for your own programs. `aurpkgs` refers
to programs that are in the AUR, and `mainpkgs` refers to programs that are in
the main repository.
