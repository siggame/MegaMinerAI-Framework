MegaMinerAI-Framework
=====================

Contains the submodules for all the components of MegaMinerAI.  This should serve as the formal release hub for all the various components.  If we release a version number (e.g. 1.0), then this will capture all the sha1's of the different repositories at version 1.0

To use:

    git clone git@github.com:siggame/MegaMinerAI-Framework.git (or whatever protocol)
    cd MegaMinerAI-Framework
    git submodule init
    git submodule update

This will clone all the submodules.  You can just do a git pull --recurse-submodules to update to the latest version.

Alternatively, 

    git config recurseSubmodules true
    
will automatically pull all the submodules when you pull from the root.  Enjoy. :D