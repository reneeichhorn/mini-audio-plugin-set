# mini-audio-plugin-set
A collection of small audio plugins written in rust

## List of plugins

### MIDI Peak Filter

**Source**: `plugins/filters/midi-peak-eq`

Use MIDI notes to control several peak filters (maximum 8 at once) so that for example when you play A4 the frequencies around 440Hz of your target audio are boosted.
