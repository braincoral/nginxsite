# NGINX Virtual Host Management Utility
A simple utility for creating and deleting symlinks to nginx virtual host files.

This works similarly to the a2ensite and a2dissite scripts for Apache2. I have also written a bash completion script that will auto-complete the commands and virtual host file names.

Usage: `ngxsite [enable/disable] [virtual host file]`

# Installation
1. Place `ngxsite` in `/usr/local/bin/`
2. `chmod +x /usr/local/bin/ngxsite`
3. (*Optional*) Place `extra/ngxsite-completion` in `/usr/share/bash-completion/completions/`. Rename it to `ngxsite`.

