[HITSIG!](https://www.facebook.com/hitsig) Fixture Controller
=============================================================

Toolchain:
----------

* [MadMapper](http://madmapper.com) for precise positioning

* [TouchOSC](http://hexler.net/software/touchosc) on iPad, For controlling the show

* [WaveClock](http://wavesum.net/waveclock-audio-to-midi-clock.html) (sound -> MIDI beat provider)

* [Modul8](http://www.modul8.us) Triggering clips through Syphon -> QC / MadMapper (1.3+)

* [DMX2MIDI](https://github.com/LeipeLeon/Modul8_Modules) in Modul8 (untested yet, I don't have an DMX host controller)

Setup/Usage:
------------

- Position/mount the beamers as seen in the [images in the docs folder](docs/v2/2012-10-05 21.33.48.jpg).
- Open the Quartz composition in Quartz Composer (as of version 1.3 this can be loaded directly into MadMapper).
- Connect the iPad core midi with "Audio/Midi setup".
- Open MadMapper and load the configuration.
- Open OSCTouch on the iPad and touch [all controls to activate every element](docs/v2/2012-10-28 19.51.31.jpg).
- Tune MadMapper to position everything.
- (optional) Open Modul8 and add some clips to the library.
- (optional) Assign the proper DMX channels for RGBA in DMX2MIDI (needs editing in the module code)
- Happy Controlling!

Adding new images:
------------------

- create a folder in assets/ImageSequences and place all images over there
- edit ImageSequences.xml and add the images with a text editor
  (TODO: use the QC DirectoryScanner instead of XML)

For more info:
--------------

	Leon Berenschot
	leipeleon@gmail.com
	http://wendbaar.nl
	06-30326921
	skype: leipeleon
	
<img src="https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-ash3/558476_421846574518956_1416993217_n.jpg"/>
<img src="https://fbcdn-sphotos-a-a.akamaihd.net/hphotos-ak-ash3/564228_421846667852280_518734943_n.jpg"/>
