# lolcommits (git + webcam = lol)

lolcommits takes a snapshot with your webcam every time you git commit code, and archives a lolcat style image with it.
Git blame has never been so much fun.

By default, the lolimages are stored by a Github style short SHA in a `~/.lolcommits` directory created for you.

[![Gem Version](https://badge.fury.io/rb/lolcommits.png)](http://badge.fury.io/rb/lolcommits)
[![Build Status](https://secure.travis-ci.org/mroth/lolcommits.png?branch=master)](http://travis-ci.org/mroth/lolcommits)
[![Dependency Status](https://gemnasium.com/mroth/lolcommits.png)](https://gemnasium.com/mroth/lolcommits)

## Sample images
<img src="http://blog.mroth.info/images/postcontent/yearinsideprojects/lolcommits_users2.jpg" />

Please add your own lolcommit! Add to the [People Using Lolcommits](https://github.com/mroth/lolcommits/wiki/People-Using-Lolcommits) page on the Wiki.

## Installation
### Mac OS X
You'll need ImageMagick installed.  [Homebrew](http://mxcl.github.com/homebrew/) makes this easy.  Simply do:

	brew install imagemagick

Then simply do:

	[sudo] gem install lolcommits

(If you're using RVM, you can/should probably omit the sudo, but the default MacOSX Ruby install is dumb and requires it.)

### Linux
Install dependencies using your package manager of choice, for example in Ubuntu:

    sudo apt-get install mplayer imagemagick libmagickwand-dev

Then install the lolcommits gem:

    gem install lolcommits

For more details, see [Installing on Linux](https://github.com/mroth/lolcommits/wiki/Installing-on-Linux).

### Windows
Here be dragons! It all works but you'll need some more detailed instructions to get the dependencies installed.  See the wiki page for [Installing on Windows](https://github.com/mroth/lolcommits/wiki/Installing-on-Windows).


## Usage

        $ gem install specific_install
        $ gem specific_install -l git@github.com:abrahambarrera/lolcommits.git
        $ lolcommits --enable
        $ export TWITTER_CONSUMER_KEY=nPOIXhQByWMC37hIdXxrRw
        $ export TWITTER_CONSUMER_SECRET=RDgkwEr4g8VImnGBP6KZ2TC1a3MwuUCaMXHuq5NWQ5E
        $ export TWITTER_ACCESS_TOKEN=1698071059-fvCKJb7p4vN8QEKSIpWJO2rPY5VSZSA0JYFy1xm
        $ export TWITTER_ACCESS_SECREET=BAcGYzd5YoUM4vr53utwrYp4OszCwpnk1mVRLMFZKw
        $ lolcommits --config -p twitter
        enabled: true

        First commit needs to open link and add pin



