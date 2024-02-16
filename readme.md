# Custom Sound Library, by DJ Dixie-Flatline.
## Preface (What the fuck is a soundfont?)
So in musical terms, MIDI actually does two things and neither are what you would expect.  MIDI doesn't transmit a signal, it transfers bytecode.
Meaning that a MIDI connection between a synthesizer and a computer won't allow you to record your sound to the computer but it would let you
record the notes and motions that make up your sound.  By itself, MIDI is actually more like a machine-readable version of sheet music; the
document itself enscapulates the music being made without actually making any sound itself.

Kind of like how composers of Orchestral pieces write down the music they hear in their head in a format accessible to conductors who are free to
render the piece as they see fit using whatever chairs available to their disposal, a MIDI file acts as a trigger to a soundfont and a soundfont
is to the orchestra as MIDI is to sheet music.

A soundfont is a collection of sound samples mapped to MIDI channel input, and while they can be combined with a pro-composed MIDI file to produce
sound they also can serve as a cross-platform repository of sounds accessible through a computer by any MIDI capable controller.

If it just so happens that your MIDI controller is also a really powerful synthesizer whose only limitation is monophony, you can alchemize it
with a computer to be able to trigger more than one of its sounds at a time.  Really powerful stuff here, we're basically hacking our own firmware
for an analog device.
