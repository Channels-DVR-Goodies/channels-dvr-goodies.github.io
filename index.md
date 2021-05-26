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


### A Plea: Please Be Reasonable

This is a hobby project that I do in what litte spare time I have. There is no quality assurance, technical support or customer
service department. There is no billing department either, please keep these things in mind.

There's no contract, warranty, nor guarantee of fitness for any purpose. You assume all liability should you choose to use this
software. Your mileage may vary. Batteries not included.

I'm making these things available in case you have a similar itch to scratch. While I'm helpful by nature, it's not reasonable to
expect me to teach you how to write code, or debug your code for you.

While I'm interested to hear your ideas for features or improvements, I'm not required to agree with you, or obliged to implement
them. Remember that I've provided the source code with few strings attached - feel free to make changes and submit pull requests,
or find someone with decent programming skills if you don't. I cannot guarantee that every pull request will be accepted, though -
best to check with me first, or risk disappointment later.

Be aware that if you can't describe a problem clearly enough that I can reproduce it, I can't help you. Nor do I have the time or
resources to recreate your 1.2 petabyte NAS running an ancient version of FreeBSD on ZFS, where one of my tools only fails when
processing odd-numbered episodes of your favorite Elbonian soap opera.

It saddens me to have to state these things, but past experience has shown that it's necessary. The goodies provided here are
working for me; but I can't hope to do extensive testing of every possible configuration people could concieve of.

In other words, please be reasonable.

If this stuff helps you, that's great, it makes me happy to think I'm helping someone. If it doesn't, I'd like to know,
particularly if it's something other people will run into. But I can't guarantee it's something I can fix, or even that
I can spare the time to do it anytime soon. 

**One last thing:** don't pass this off as your work. And yes, sadly it's necessary to state that.
