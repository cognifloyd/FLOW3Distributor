What's this all about?
----------------------
The goal of this small bash script is to simplify the process of creating a new base distribution for a new project. If you're "just" creating a package for FLOW3 that will be part of an existing FLOW3 installation, you probably won't need this. It is intented for situations where you want to start a project that can be shipped out of the box by delivering a full blown distribution that contains all the needed components like the FLOW3 Framework, Fluid templating engine and some basic config files.

**Attention:** Of course you need to "add life" to this new empty distribution by adding your package(s) and changing the config files to your need. It's more like a kickstarter, not a wonder-machine.


How to use?
-----------
Basically you just need to checkout the "Distributor" Package and to run the shell script

    git clone git@github.com:mrimann/FLOW3Distributor.git FLOW3Distributor
    cd FLOW3Distributor
    ./FLOW3Distributor.sh
	
This will create the following directory structure:

::
    FLOW3Distributor
        Distribution		<-- contains your new empty distribution
        TYPO3Distributor.sh
        README.rst

Just move your Distribution directory to wherever you need. It's a full blown Git repository that already contains the first commit.


Feedback?
---------
Please yes - just send it to mario@rimann.org and let's see what I can make out of it. Of course, nice "thank you" mails are appreciated most :-)


Found a bug or want an additional feature?
------------------------------------------
Don't worry, just open an issue on GitHub (https://github.com/mrimann/topic-voting/issues) or even better: Fix it and contribute it back to the project. You can fork the sourcecode from the Git repository and send me a pull request as soon as you've finished (I have to find out how to work with this first, you might be the first contributor)