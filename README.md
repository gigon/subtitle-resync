### [Subtitle Resync](https://github.com/gigon/subtitle-resync)

Offline client-side tool to shift the subtitles in an .srt file by a fixed time offset
or set fixed duration of display for all srt lines

#### Motivation:

* I wanted to test what happens when subtitles are shown for very brief duration
  such that they are non perceivable by human eyes.
  The assumption is that if you watch a movie in a foreign language
  with subtitles in your own language, 
  subliminal cues will enable learning the foreign language 

* Unfortunately when playing a SRT with the fixed duration set to 7 milliseconds or lower
  VLC does not seem to display the subtitles at all.
  I saw this by playing the movie in 0.5 normal speed.
  The smallest duration that is displayed is 8 ms, but then Ican perceive the subtitles
  flashing , which is not desired for subliminal suggestion.
   
#### Comments:

* Forked from https://github.com/warren-bank/subtitle-resync

#### Legal:

* copyright: [gigon](https://github.com/gigon)
* license: [GPL-2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)
