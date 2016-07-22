# dal-young-makers
Dallas Young Makers Source Repo

##Introduction

This repo hosts source code and project materials used in classes taught by the Dallas Young Makers Group.  All code is published under GPL.

Included is a utility to automate the flashing RCX bricks [flash-menu](../master/tools/flash-menu).  This will flash the brick with the appropriate firmware and load the programs used in the specified class.


##Installation

The steps below allow you to flash RCX on any Debian based linux machine.

1. Install prerequisite packages: `sudo apt-get install git nqc dialog unzip wget`
2. Clone the repo: `git clone https://github.com/buddyw/dal-young-makers.git`
3. Run `./dal-young-makers/tools/flash-menu` to start flashing RCX bricks

You will need internet connectivity the first time you flash a class as the correct RCX firmware package will be automatically downloaded and stored in a `tmp` folder. After it has been downloaded, no internet access is necessary to flash that class.
