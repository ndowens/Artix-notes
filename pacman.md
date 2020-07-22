# Remove orphans
pacman -Rs $(pacman -Qqtd)
