#cm.grainlabs~
**by Matthias W. Müller - [@mwmueller](https://twitter.com/mwmueller) - [cmlabs.wordpress.com](https://cmlabs.wordpress.com/)**

###About
cm.grainlabs~ is an external audio object for [Cycling 74's Max](https://cycling74.com), used for polyphonic granulation of pre-recorded sounds. It is loosely based on Curtis Roads’ asynchronous granular synthesis (see Curtis Roads' book [Microsound](http://mitpress.mit.edu/books/microsound) for more information). It granulates both single- and dual-channel audio files loaded into a buffer~ object and makes use of a second buffer~ object for the windowing function applied to each grain.

Available controls are the following and consist of an upper and lower range, from within which a random value is generated for each grain:
* start position within the selected sample buffer~ object
* grain length
* grain pitch
* pan

###System Requirements for Compiled Externals
* Mac OS 10.9.5 or above
* Max 6.1.8 or above (compatible with Max 7)
* Max running in 64 bit mode

###Installing the Source (Mac OS X)
If you have [Git](http://git-scm.com/) installed, you can install via the Terminal using the following commands:

	cd ~/yourdirectory
	mkdir cm.grainlabs~
	cd cm.grainlabs~
	git clone https://github.com/CircuitMusicLabs/cm.grainlabs

If you do not have Git installed, you can [download this ZIP archive](https://github.com/CircuitMusicLabs/cm.grainlabs/archive/master.zip). It contains the latest changes from the master branch.

After you downloaded the entire repository, open the included Xcode project and compile the external with via Product > Build (Command-B).

###Installing the Max Package
Installation instructions Max 6
* Copy the entire cm.grainlabs~ folder either into the "packages" folder in your Max installation or into "Max/Packages" in your ~/Documents folder.

Installation instructions Max 7
* Copy the entire cm.grainlabs~ folder into “Max 7/Packages" in your ~/Documents folder.

###Compatibility
Externals are currently only compiled for the 64 bit Mac OS X version of [Max](https://cycling74.com) version 6 or 7. If you would like to help with Windows and/or backwards compatibility, please don't hesitate to contact me or to fork the repository. Compatibility issues are also listed in [the Issues section](https://github.com/CircuitMusicLabs/cm.grainlabs/issues) of this GitHub project site.

###Bug reporting
If you feel that you have found a bug, please report it via [the Issues section](https://github.com/CircuitMusicLabs/cm.grainlabs/issues) of this GitHub project site.
