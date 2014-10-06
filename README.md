# Sublime Text Preferences

Check out this repository and symlink it to Sublime Text's Application Support folder to get your settings quick and get to work.

**NOTE:** This can be run on its own, but is automatically included in my **[Setup script](https://github.com/matthewmcvickar/setup)**.

## Instructions

1. Close Sublime Text.

1. Check out this repo:

    ```sh
    $ cd ~/Sites/matthewmcvickar
    $ git clone git@github.com:matthewmcvickar/sublime-text-preferences.git
    ```

1. Symlink:

    ```sh
    $ cd /Users/matthewmcvickar/Library/Application\ Support/Sublime\ Text\ 3/Packages
    $ rm -r User
    $ ln -s ~/Sites/matthewmcvickar/sublime-text-preferences/ User
    ```

1. Fix SASS highlighting. Go into `Application Support/Sublime Text 3/Packages/Rails/Ruby Haml.tmLanguage` and remove line 8: `<string>sass</string>`.

1. Start up Sublime Text.
