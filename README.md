## About

This repository contain default desktop minos settings, some of the changes affect:

- Skel default files:
 - `.Xdefault`: default theme and urxvt options
 - `.xsession`: i3 session
 - `.config/redshift.conf`: redshift template
 - `.config/Trolltech.conf`: default qt theme
 - `.config/user-dirs.dirs`: stop autocreation of ~/Video, ~/Audio, etc folders

- Application settings:
 - `git`: default theme plus aliases
 - `i3`: default theme, shortcuts, statusbar, etc
 - `compton`: performance oriented settings
 - `mplayer`: fifo controller
 - `ncmpcpp`: default theme
 - `pcmanfm`: default settings
 - `irssi`: default theme
 - `mutt`: multiple account email settings template
 - `urxvt`: common plugins and default theme
 - `minos`: autostart/statusbar/help settings

## Quick start

### On Ubuntu (only LTS releases)

1. Set up the minos archive:

   ```
   $ sudo add-apt-repository ppa:minos-archive/main
   ```

2. Install:

   ```
   $ sudo apt-get update && sudo apt-get install minos-desktop-settings
   ```

3. Enjoy ☺!

## Feedback

Please drop me an [email](mailto:m@javier.io) with your suggestions or open [an issue](https://github.com/minos-org/bash-minos-settings/issues) with your comments.
