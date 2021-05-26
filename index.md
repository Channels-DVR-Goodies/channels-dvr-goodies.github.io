# Paul's (unofficial) goodies for the Channels DVR

 > **Your attention please:** these goodies are not provided by, and in no way are endorsed or supported by Fancy Bits LLC,
 > the developers of the Channels DVR. If any part of these goodies don't work for you (or later stops working), that's
 > my obligation and perogative to fix, not theirs.

If these goodies start to become a support burden from them, they would be well within their rights to ask me to 'cease and decist',
which I will gladly do. I value the work they put into Channels DVR, and don't want to do anything that might get in the way of them
continuing to improve an already-excellent product.

## [DVR2Plex](https://channels-dvr-goodies.github.io/DVR2Plex)

## [cuckoo](https://channels-dvr-goodies.github.io/cuckoo)

An executable that impersonates another, so that additional executables can also be called whenever it is invoked.

## [json2shell](https://channels-dvr-goodies.github.io/DVR2Plex)

Converts a simple JSON file to text that can be 'eval'd by bash to set matching environment variables.

Channels DVR can generate a JSON file alongside the recording if configured to do so. This JSON file contains
some of the guide data about the recording such as whether it's a movie, season and episode number, a short
description, original broadcast date, etc.

This goodie reads a JSON file in the style of the MCEBuddy file that Channels DVR creates, and outputs the
equivalent shell variable definitions, ready to be used in an 'eval' statement in your very own script.

There are some example scripts provided.

## [mungeM3U](https://channels-dvr-goodies.github.io/mungeM3U)

Postprocessor for M3U files. also includes the [mungeFCC](https://channels-dvr-goodies.github.io/mungeFCC) tool

## [edl2mkvchapters](https://channels-dvr-goodies.github.io/edl2mkvchapters)

Converts EDL file (like Channels DVR emits) to a chapters file for mkvmerge
