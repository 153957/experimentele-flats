Experimentele flats
===================

[![GPLv3](http://img.shields.io/badge/license-GPLv3-blue.png)]
(https://github.com/experimentele-flats/experimentele-flats/blob/master/LICENSE)
[![Travis Status](http://img.shields.io/travis/experimentele-flats/experimentele-flats/master.png)]
(https://travis-ci.org/experimentele-flats/experimentele-flats)

This is the website for the experimentele flats in Utrecht Overvecht.


Installing cactus
-----------------

This site uses [Cactus](https://github.com/koenbok/Cactus/) to build.

Cactus is a Python program, so Python 2.7 is required.
Also pip is used to install cactus.
Other packages that are required by cactus are automatically installed.
So open a Terminal and run:

    pip install https://github.com/koenbok/Cactus/archive/v3.zip

If all goes well cactus can now be used.

To start a local webserver navigate to the repository in the Terminal
and run:

    cactus serve

You can then point your browser to http://127.0.0.1:8000 to view the
local version. If you make any changes to the code this should be
reflected almost immediently in the local website.


Synchronize
-----------

To update the live server use these commands:

    cd [path to repository]
    rm -rf .build
    cactus build
    rsync -avz .build/ [username]@[server address]:[path to web root]


Colors & Fonts
--------------

We use these colors:

    Green: #26a522
    Yellow: #fdc90c

Also used but less important:

    Black: #000000
    Blue: #0037ff

And these fonts:

    Title and menuitems: Museo 700 Regular (serif)
    Button text on main page: MuseoSans 500 (sans-serif)
