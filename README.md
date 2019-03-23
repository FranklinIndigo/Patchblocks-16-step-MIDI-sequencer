# Patchblocks-16-step-MIDI-sequencer
Patchblocks 16 step MIDI sequencer

I programmed a patch for the Patchblocks. It is a 16 step MIDI sequencer patch. 

It has the following features:

3 modes, indicated by left LED and selected by left button:
 1. LED off: Free play notes
 2. LED on: record notes (max 16, but also less is possible)
 3. Flashing LED: playback sequence

Can be synced with Korg Volca (when audio input is detected)

When in free play mode:
 - select MIDI channel on the fly with right button
 - right LED flashes to indicate selected MIDI channel

When recording steps:
 - use right button to input REST notes
 - right LED flashes short on 16th note to indicate end of sequence

When sequence is playing:
 - left knop: change tempo or change 1/4n, 1/8n, etc. when synced with Korg Volcas (or free tempo without sync)
 - right knop: turn right to playback all 16 notes or turn left to playback less notes
 - transpose sequence on the fly, stays in sync


See this video for a demo: https://youtu.be/Xyrsp6ussVY
