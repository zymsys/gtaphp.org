gtaphp.org
==========

This repo contains the web site for the [GTA-PHP Meeetup Group](http://gtaphp.org/).
It was set up to host our pre-talk slide deck so that people can contribute
slides with pull requests, and speakers can play the slides from their own
notebooks easily. Thanks to Alfred Ayache for creating the initial slide
deck for the group.

Installation
------------

To make a local working copy of the site, clone the git repo and install
the JavaScript requirements with bower.

    git clone https://github.com/zymsys/gtaphp.org.git
    cd gtaphp.org
    bower install
    
At this point you should be able to view the slide deck in a browser by opening
slides/index.html. There's no server requirements to the slide deck, and
the paths are all relative, so it should work straight off your filesystem.

Contributing / Editing Slides
-----------------------------

Create a fork of the repo on github, clone that and make your revisions there.
Then when you're happy with the results, send a 
[pull request](https://help.github.com/articles/using-pull-requests/).

You can find the slide information in slides/index.html, and the markup should
be straightforward if you know html.