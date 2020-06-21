Experimentele flats
===================

[![GPLv3](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://github.com/experimentele-flats/experimentele-flats.github.io/blob/master/LICENSE)
[![GitHub build](https://img.shields.io/github/workflow/status/experimentele-flats/experimentele-flats.github.io/Build site and check output)

This is the website for the [experimentele flats](https://www.experimentele-flats.nl/) in Utrecht Overvecht.


Building the site
-----------------

Whenever changes are made to the source branch GitHub will automatically
build the website and put it in the master branch.


Installing cactus
-----------------

This site uses [Cactus](https://github.com/eudicots/Cactus/) to build.

Cactus is a Python program, so Python is required and pip is used to install Cactus.
Other packages that are required by Cactus will be automatically installed.
So open a Terminal and run:

    pip install -r requirements.txt

If all goes well Cactus can now be used.

To start a local webserver navigate to the repository in the Terminal
and run:

    cactus serve

You can then point your browser to http://127.0.0.1:8000 to view the
local version. If you make any changes to the code this should be
reflected almost immediently in the local website.


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
