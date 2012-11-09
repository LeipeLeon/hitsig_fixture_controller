HITSIG! Fixture Controller

https://www.facebook.com/hitsig

Toolchain:

* Modul8
  Triggering clips through Syphon -> QC

* MadMapper
  for precise positioning

* WaveClock (sound -> MIDI beat provider)
  http://wavesum.net/waveclock-audio-to-midi-clock.html

* OSC on iPad
  Controlling the show

* DMX2MIDI in Modul8 (untested yet, I don't have an DMX host controller)
  https://github.com/LeipeLeon/Modul8_Modules


Setup/Usage:

- Position/mount the beamers as seen in the images in the docs folder.
- Open the Quartz composition in Quartz Composer (as of version 1.3 this can be loaded directly into MadMapper).
- Connect the iPad core midi with "Audio/Midi setup".
- Open MadMapper and load the configuration.
- Open OSCTouch on the iPad and touch all controls to activate every element.
- Tune MadMapper to position everything.
- (optional) Open Modul8 and add some clips to the library.

Adding new images:
- create a folder in assets/ImageSequences and place all images over there
- edit ImageSequences.xml and add the images with a text editor
  (TODO: use the QC DirectoryScanner instead of XML)

