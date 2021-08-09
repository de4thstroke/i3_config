# i3_config
i3 is a dynamic tiling window manger. I've added configuration files that I used for my system. You can add these files in corresponding folders.

# config
config is configuration file for i3. Replace the existing file in .config/i3/config with this file after installing i3. You can add keyboard shortcuts and some functions that should run when i3 is started, could be specified in this file.

# i3blocks
i3blocks is a flexible and clickable status bar available with i3. I have used noto-fonts-emoji to have coloured emojis in status bar. The bash scripts in blocks folder is used in i3blocks.
![Screenshot_2021-08-09_12-40-29](https://user-images.githubusercontent.com/46030987/128672030-07c8fe44-70ee-4f70-9692-d2131be9be0b.png)

# Blocks
In this repository, blocks contain the scripts that are necessary for i3blocks. Save these scripts in ~/.local/bin or /usr/bin or /bin folder. i3bat file in Blocks folder uses font-awesome. You could install it from arch repository or using github. Font-awesome is useful if you like to have monochrome emojis in some cases.

# Coloured emojis
To have coloured emojis, first install noto-fonts-emoji. Then save the file fonts.conf as /etc/fonts/local.conf(or ~/.config/fontconfig/fonts.conf if you want to have emojis only current user) in your system. To apply new changes run fc-cache -f -v in terminal.
[Source:https://web.archive.org/web/20191112095758/https://forum.manjaro.org/t/tutorial-how-to-enable-system-wide-color-emoji-support/35188]
