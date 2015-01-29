# geometry
===
# music
===
# modules
===

===
♩♪♫♬
===

# beat (♥beat)
### returns 
`int` beat (sent on every beat, # of milliseconds between beats)

`int` bpm (sent on tempo change, beats per minute)

### responds to
`bool` _click_track (activates dsp, makes a speaker noise on the beat)

`bool` STOP_BEAT (disables beat metronome entirely)

# phrasing
### returns
`bang` downbeat, downmeasure, downphrase

`int` beat_position, measure_position, phrase_position

`int` beat_number, measure_number, phrase_number

### responds to
`bang` beat

`bang` MASTER_RESET, PULSE_RESET

# sector
### returns
`bang` sector_beat

### responds to
`bang` beat, measure, phrase

MASTER_RESET, PULSE_RESET

# interface: organ pedal
### returns
‘int’ inputkey

‘string’ currentkey

### responds to
keyboard input: `A` - `L`
