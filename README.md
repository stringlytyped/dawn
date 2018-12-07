# Dawn

<img src="https://raw.githubusercontent.com/stringlytyped/dawn/master/screenshot.png?token=ABLpZOrKOJUkxA5z4q6qkhGdH95kxJf9ks5cE9DpwA%3D%3D" alt="Screenshot" width="776">

Dawn is a macOS setup script which automatically configures a clean install of the OS, installing applications and CLI tools, adding favourite fonts and setting sensible system defaults. It forms part of my larger macOS setup which consists of:

- **dawn** (this repo): a script that walks you through the process of setting up a newly-installed copy of macOS from scratch
- **[toolbox](https://github.com/stringlytyped/toolbox)**: miscellaneous shell scripts that perform various functions (some of questionable utility)
- **[dotfiles](https://github.com/stringlytyped/dotfiles)**: shell preferences, including useful aliases for common tasks

## How to use

```bash
git clone https://github.com/stringlytyped/dawn.git dawn
cd dawn
./setup
```

## Tasks

The script will perform the following tasks, prompting you for permission before making any changes:

### Configure the command line

1. Install the Xcode command line tools
2. Install Homebrew
3. Install GNU Bash 4
4. Change the default shell to Bash 4
5. Disable "last login" message when openning a new Terminal.app window
6. Install GNU coreutils
7. Install GNU findutils
8. Install GNU grep
9. Install wget
10. Install [trash](http://hasseg.org/trash/)
11. Install tree command (show directory listings as a nested tree)
12. Install Git
13. Install [hub](https://hub.github.com/)
14. Install [wiki](https://github.com/walle/wiki)
15. Install [weather](https://github.com/genuinetools/weather)
16. Install cowsay
17. Install fortune
18. Install nyancat
19. Install neofetch
20. Install custom Black Frost terminal theme

### Install apps

1. Install Firefox Developer Edition
2. Install Google Chrome
3. Install Opera
4. Install various Quick Look plugins
5. Install App Cleaner
6. Install Hazel
7. Install Spotify
8. Install Sublime Text 3
9. Install Package Control for Sublime
10. Install Cyberduck
11. Install Tunnelblick
12. Install VLC
13. Install Transmission
14. Install OSXFUSE and sshfs
15. Install Doxie
16. Install Evernote
17. Install Minecraft
18. Install Steam
19. Install Origin
20. Install Handbrake
21. Install Subler
22. Install SourceTree
23. Install TeamViewer
24. Install Keka
25. Install The Unarchiver

### Install fonts

1. Install Cabin, Cabin Condensed, Cabin Sketch
2. Install Font Awesome
3. Install Open Sans, Open Sans Condensed, Open Sans Hebrew, Open Sans Hebrew Condensed
4. Install Meslo Nerd, patched for [powerline](https://github.com/powerline/powerline)

### Set macOS defaults

1. Prompt for hostname
2. Prompt for new disk name (in place of "Macintosh HD")
3. Disable Spotlight indexing for newly mounted drives
4. Expand the save and print panels by default
5. Automatically quit the printer app once all print jobs are completed
6. Change default behaviour of save panels to save to disk, rather than iCloud
7. Check for software updates daily, not weekly
8. Enter standby mode after 12 hours instead of after 1
9. Enable keyboard access for GUI controls
10. Require password immediately after sleep or screen saver begins
11. Create symbolic link to the user's Applications folder (~/Applications) in the system Applications folder (/Applications)
12. Show filename extensions in Finder
13. Disable warning when changing a filename extension
14. Use column view in all Finder windows by default
15. Allow text selection in Quick Look
16. Set default Finder location to the user's home directory
17. Turn on snap-to-grid for icon views
18. Add commonly-used applications to the Dock
19. Prevent Time Machine from prompting to use new hard drives as backup volume
20. Hide Transmission's donate message 
21. Hide Transmission's legal disclaimer
20. Restart applications to have changes take effect
