LegendROM
========

Getting Started
---------------

To get started with Android/LegendROM based on AOSP, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use this command:

	repo init -u https://github.com/LegendROM-AOSP/manifest.git -b 8.1

Then to sync up:

	repo sync

Set up build enviroment

	. build/envsetup.sh

Select device

	lunch

Compile the rom

	mka bacon
