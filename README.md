# xenia-plymouth
plymouth boot theme featuring Xenia

# installation

detailed instructions on customising plymouth at my [projects page on the subject](http://tranarchy.fish/~rowan/projects/redecorating.html).

NB. requires a plymouth setup that supports `ModuleName=script` (some distros seem to have problems with this e.g. Canonical Gnome Ubuntu)

- make the directory `/usr/share/plymouth/themes/xenia-logo`
- copy the files from this repository into it
- run `sudo ln -sf /usr/share/plymouth/themes/xenia-logo/xenia-logo.plymouth /etc/alternatives/default.plymouth`
- run `sudo update-initramfs -u`

plymouth should now be set to use the theme
