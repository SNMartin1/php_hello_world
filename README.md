# php_hello_world

# Project Information

This repository is where I am setting up information as I learn the basics of PHP
(including installing information, basic syntax, etc) and will do a hello world
application.


### Install Instructions

# Mac OS X Instructions

PHP is bundled with Macs. If you need to reinstall PHP on your mac, here is a
resource explaining reinstall (instructions from 2011, may need updated instructions).

http://justinhileman.info/article/reinstalling-php-on-mac-os-x/

1. Need to install Homebrew. https://brew.sh
2. Default option:
      - brew tap homebrew/dupes
      - brew tap homebrew/versions
      - brew tap homebrew/homebrew-php
      - brew install php56
          - (may need to research the current update; last comment I saw stated that
            they had to use php70 instead)
3. If you run into problems, try updating Xcode Command Line Tools and reinstall
      - brew uninstall php56
      - brew cleanup
      - xcode-select --install # An "install" window will appear. Click "yes" on all the things.
      - brew install php56
4. Link mentioned above has some more trouble shooting options.


# Resources

PHP Documentation Site

http://php.net/manual/en/install.php

Reinstall/install

Mac OS X - http://justinhileman.info/article/reinstalling-php-on-mac-os-x/
Other systems - http://php.net/manual/en/install.php
