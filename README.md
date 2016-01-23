#cm.grainlabs~
**by Matthias W. Müller - [@mwmueller](https://twitter.com/mwmueller) - [cmlabs.wordpress.com](https://cmlabs.wordpress.com/)**

###About
cm.grainlabs~ is an external audio object for [Max by Cycling '74](https://cycling74.com), used for polyphonic granulation of pre-recorded sounds. It is loosely based on Curtis Roads’ asynchronous granular synthesis (see Curtis Roads' book [Microsound](http://mitpress.mit.edu/books/microsound) for more information). It granulates both single- and dual-channel audio files loaded into a buffer~ object and makes use of a second buffer~ object for the windowing function applied to each grain.

Available controls are the following and consist of an upper and lower range, from within which a random value is generated for each grain:
* start position within the selected sample buffer~ object
* grain length
* grain pitch
* pan
* gain

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

###Installing the Max Package (Max 6 - Mac OS X)
Copy the entire cm.grainlabs~ folder inside the "max-package" directory either into the "packages" folder in your Max installation or into "Max/Packages" in your ~/Documents folder.

###Installing the Max Package (Max 7 - Mac OS X)
Copy the entire cm.grainlabs~ folder inside the "max-package" directory into “Max 7/Packages" in your ~/Documents folder.

###Compatibility
The source code for cm.grainlabs~ can currently only be compiled for the 64 bit Mac OS X version of [Max](https://cycling74.com) version 6 or 7. User [alfonso73](https://github.com/alfonso73) has successfully compiled for Windows and kindly offered the Windows compatible externals for download. The Max package is included in this repository. Compatibility issues are also listed in [the Issues section](https://github.com/CircuitMusicLabs/cm.grainlabs/issues) of this GitHub project site.

###Bug reporting
If you feel that you have found a bug, please report it via [the Issues section](https://github.com/CircuitMusicLabs/cm.grainlabs/issues) of this GitHub project site.
