# php_hello_world Project Information

This repository is where I am setting up information as I learn the basics of PHP
(including installing information, basic syntax, etc) and will do a hello world
application.


# Install Instructions

### Mac OS X Instructions

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

### PHP Documentation Site

http://php.net/manual/en/install.php

### Reinstall/install

- Mac OS X - http://justinhileman.info/article/reinstalling-php-on-mac-os-x/
- Other systems - http://php.net/manual/en/install.php

# Technology Stack

### What PHP is good at

- PHP's development is focused on server-side scripting.
- (Resource: http://php.net/manual/en/intro-whatis.php)

- Three main areas where PHP scripts are used.
      1. Server-side scripting
      2. Command line scripting
      3. Writing desktop application
- (Resource: http://php.net/manual/en/intro-whatcando.php with more information)

- PHP is used on 80% of the top websites and used by popular content management systems to se up websites or shopping carts. It was designed for the web.

- Considerations - As a dynamically typed language, PHP is too flexible and the machine would need to do a lot of referencing to make sure what the definition of something is, and this slows PHP performance down.
- (From: http://www.bestprogramminglanguagefor.me/why-learn-php)

# Basic File Extension/Syntax

- The default file extension for PHP files is ".php".
- (Resource https://www.w3schools.com/php/php_syntax.asp)

- A PHP file normally contains HTML tags, and some PHP scripting code.


### Opinions on PHP as a programming language

- Why do so many developers hate PHP?
- https://www.reddit.com/r/PHP/comments/1fy71s/why_do_so_many_developers_hate_php/?st=j7m6qi17&sh=daff1dee

- Please stop pretending PHP is a good language
- http://edorian.github.io/2013-10-19-Please-stop-pretending-PHP-is-a-good-language/

- PHP is much better than you think
- http://fabien.potencier.org/php-is-much-better-than-you-think.html
