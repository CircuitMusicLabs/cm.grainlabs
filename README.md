#cm.grainlabs~
**by Matthias W. Müller - [@mwmueller](https://twitter.com/mwmueller) - [cmlabs.wordpress.com](https://cmlabs.wordpress.com/)**

##About
cm.grainlabs~ is an external audio object for [Cycling 74's Max](https://cycling74.com), used for polyphonic granulation of pre-recorded sounds. It is loosely based on [Curtis Roads’ asynchronous granular synthesis](http://www.granularsynthesis.com/hthesis/sync.html). It can granulate both mono and stereo audio files loaded into the sample buffer~ object. When a stereo file is loaded into the sample buffer~ object and the ‘stereo’ attribute is activated, cm.grainlabs~ will generate a grain from both channels and send each channel to the respective output.

cm.grainlabs~ makes use of a second buffer~ object for the windowing function applied to each grain. The package available for download contains a full collection of windowing samples. The use of a buffer~ object for windowing also allows for using other sources for windowing than the ones provided with the package.

In addition, cm.grainlabs~ tells us about the number of grains which are currently playing. This facilitates voice management when the external is located inside a poly~ patcher.

Available controls are the following and consist of an upper and lower range, from within which a random value is generated for each grain:
* start position within the selected sample buffer~ object
* grain length
* grain pitch
* pan

System Requirements:
* Mac OS 10.9.5 or above
* Max 6.1.8 or above (compatible with Max 7)
* Max running in 64 bit mode

##Bug reporting
If you feel that you have found a bug, please report it via [the Issues section](https://github.com/CircuitMusicLabs/cm.grainlabs/issues) of this GitHub project site.
