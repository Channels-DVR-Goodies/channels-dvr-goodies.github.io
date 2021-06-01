# Paul's (unofficial) goodies for the Channels DVR

 > **Your attention please:** these goodies are not provided by, and are in no way endorsed or supported by Fancy Bits LLC, the
 > developers of the Channels DVR. If any part of these goodies don't work for you, that's my obligation to fix, not theirs.

If these goodies start to become a support burden from them, they would be well within their rights to ask me to 'cease and desist'.
Channels DVR is valuable to me, as is the work they put into improving it. I don't want to do anything that could get in the way
of that continuing.

## [DVR2Plex](https://channels-dvr-goodies.github.io/DVR2Plex)

DVR2Plex is a tool for doing 'magic' renaming of files from various sources into 'normalized' ones using templates.
The fuzzy matching does a pretty good job of figuring out that common misnamings in guide data belongs in the right
spot in your plex hierarchy (e.g. Something listed as 'Marvels Agents Of Shield' in the guide data will end up in
your 'Marvel's Agents of S.H.I.E.L.D.' directory.

## [cuckoo](https://channels-dvr-goodies.github.io/cuckoo)

An executable that impersonates another, so that additional executables can also be called whenever it is invoked.
Particularly useful for doing additional post-processing, by impersonating Channel DVR's private comskip executable.

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

Converts EDL file (like Channels DVR emits) to a chapters file for use with mkvmerge.

## [avcp](https://channels-dvr-goodies.github.io/avcp)

Intelligent copying of A/V files, to prevent a lower-quality A/V file from being copied over a higher-quality one. [work-in-progress]

---
 > **Note:** Because of past unpleasent experiences I've had first-hand, I wrote [A Plea: Please be Reasonable](https://channels-dvr-goodies.github.io/Please-Be-Reasonable).
 > If you think I'm somehow treating you unfairly, or that 'giving away free stuff' means I owe you something personally, please read (and
 > understand) that page first. _Only then_ contact me to complain. I reserve the right to point you to that page in response. Life
 > is simply too short.
 > 
 > To be clear, the vast majority of you are reasonable, even appreciative. I get considerable satisfaction from sharing something with
 > you that you find useful. Sadly seems like a few burdened with unreasonable attitudes can sour that satisfaction pretty quickly. 
