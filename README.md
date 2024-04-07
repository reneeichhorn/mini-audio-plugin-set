# mini-audio-plugin-set
A collection of small audio plugins written in rust

## Disclaimer

Most Plugins do not come with any UI as it is not needed. Just use your DAW's control to setup or modulate any of the plugins params.

## List of plugins

### MIDI Peak EQ

**Source**: `plugins/filters/midi-peak-eq`

Use MIDI notes to control several peak filters (maximum 8 at once) so that for example when you play A4 the frequencies around 440Hz of your target audio are boosted.

Inspired by a Video from [Virtual Riot](https://www.youtube.com/watch?v=TZ8wp32PJTU)
