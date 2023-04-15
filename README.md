# Autosetup

The name is misleading, it is just a collection of shell scripts and package
lists.

## Customization

Provide `DOTFILES_URL` before the script invocation, so it uses your
repository. Also, provide `BARE_REPO_DIR` for the bare repository locations. I
may add other methods later.

Change `aurpkgs.txt` and `mainpkgs.txt` for your own programs. `aurpkgs` refers
to programs that are in the AUR, and `mainpkgs` refers to programs that are in
the main repository.
