shrinkypic
==========

A pyside/python interface for several ImageMagick picture manipulation affects.

SHRINKYPIC INSTALLATION

Open a terminal and perform the following steps.

1) Pull from repository with:

    hg clone http://hg.palaso.org/shrinkypic ~/Projects/shrinkypic

2) Install required packages:

    sudo apt-get install python-pyside imagemagick pngnq
    
3) Install ShrinkyPic with:

    cd ~/Projects/shrinkypic
    ./setup.py build
    sudo ./setup.py install

4) Start ShinkyPic with:

    shrinkypic
