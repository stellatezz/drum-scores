# Naked Drums: playback kit

The drum sounds the score pages play.

**Source:** Naked Drums, © Wilkinson Audio 2016, in the SFZ version by kinwie published by SFZ Instruments:
https://github.com/sfzinstruments/WilkinsonAudio.NakedDrums

**Licence:** Creative Commons Attribution 4.0 International (CC BY 4.0),
https://creativecommons.org/licenses/by/4.0/. These files are offered under the same licence and come with no
warranties.

**Changes made:** every mic of the kit (close mics, overheads, close and far rooms, mid-side, wide overheads) is mixed
to stereo at the SFZ's default mixer settings, one file per instrument, velocity layer and take. Of the 10 takes per
layer, 3 to 6 are kept. Tails are cut where they fall below -66 dB of the loudest hit, then faded out, and the files
are encoded to AAC. The mapping to drum2score's instruments is: kick 36, snare 38, cross-stick 37, closed hi-hat 42,
open hi-hat 49, hi-hat foot 44, ride 51, ride bell 53, crash 55, splash 54, china 50, toms 48 / 47 / 45 / 41
(10", 12", 13" tuned down 2 semitones by the SFZ, 16"). Made with `playback/make_kit.py` in drum2score.

`kit.json` lists the files with their velocity ranges, and describes how playback chooses the layer and gain and
which sounds cut off others.
