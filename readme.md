# geometry
===
# music
===
# apps
===

===
♩♪♫♬
===

# beat (♥beat)
### returns `bang` beat

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
