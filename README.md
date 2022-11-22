# DISCLAIMER : IT IS NOT MY REPOSITORY IT IS OF ([@nboughton](https://github.com/nboughton/dotfiles))
##Main sway folders - SWAY , SWAYLOCK , WOFI , WAYBAR


# Notes:

If you want to use the custom/updates (obligatory "I use arch btw") module you'll need Go and Yay installed. You'll also need to do the following:

* ````mkdir -p ~/tmp```` as this is where I output the json data that is polled by the waybar config
* Symlink the updates.timer and updates.service files from waybar/modules/updates/ into ~/.config/systemd/user
* Run ````systemctl --user daemon-reload````
* Run ````systemctl --user enable updates.timer````

## Screenshot

![screenshot](/screenshot.png)
