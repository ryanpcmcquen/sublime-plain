sublime-plain
=============

For those who don't want syntax highlighting. ;-)

If you are thinking that you can just set syntax to 'Plain Text', smack yourself about the face ... then realize, that this does not work with fuzzy search, the end.


To install on Linux:

    wget -N https://raw.githubusercontent.com/ryanpcmcquen/sublime-plain/master/plain.tmTheme -P ~/.config/sublime-text-3/Packages/User/

To install on Mac OS X:

    wget -N https://raw.githubusercontent.com/ryanpcmcquen/sublime-plain/master/plain.tmTheme -P ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/


Then add this line to your Preferences.sublime-settings:

    "color_scheme": "Packages/User/plain.tmTheme"

Don't forget to use a comma if it is not the last line.
