DinguxCommander for Leapster Explorer
-------------------------------------


History
-------

2011-03-09 : Version 2.1
             - Rename a file/dir
             - Create new dir
             - Minor fixes

2011-02-16 : Version 2.0
             - Execute file
             - View file
             - Disk information
             - Disk used by a list of selected files/dirs
             - New button mapping
             - Small fixes

2011-02-05 : Version 1.0 : Initial version.


Introduction
------------

DinguxCommander is a file manager for Dingoo (Dingux).
It uses two vertical panels side by side, one being the source and the other the
destination, like many 'commander-style' file managers such as Norton Commander
or Midnight Commander.
DinguxCommander allows to:
    o Copy, move and delete multiple files.
    o View a file
    o Execute a file
    o Rename a file or directory
    o Create a new directory
    o Display disk space used by a list of selected files/dirs
    o Display disk information (used, available, total) (does not work on Leapster Explorer)

Installation
------------

You'll need the compiler and SDL1.2. When those are installed, clone the repository, then build as normal:
    git clone https://github.com/lfdevvel/dingux_commander/
    cd dingux_commander
    CROSS_COMPILE=arm-none-linux-gnueabi- make -f Makefile.lf1000

Controls
--------

o D-pad         Move
o L/R           Page up/page down
o B             For a directory: open
                For a file: view or execute
o A             Go to parent directory / cancel
o Hint             System actions:
                  - Select all items
                  - Select no items
                  - Create new directory
                  - Display disk information
                  - Quit program
o Pause             Actions on selected items:
                  - Copy to destination directory
                  - Move to destination directory
                  - Rename (appears only if 1 item is selected)
                  - Delete
                  - Display disk used
o Volume Up        Select highlighted item.
                Selected items are displayed in red.
o Volume Down         Open highlighted directory in destination panel.
                If a file is highlighted, open current directory in destination panel.


Credits
-------

Homepage:      http://beyondds.free.fr/
Development:   Mia
Font:          Beycan Çetin
