# circvlar rvins m4lv4 v0.6
Max for Live device for the Roland V-4 Mixer

## Hardware Requirement:
- Roland V-4 Mixer attached via MIDI
- Tested on firmware v1.1
- Computer running Max for Live

## Configuration:
Assign the following MIDI CC codes from Menu->MIDI Setup
```
MIDI Rx Channel -> 1-16 (must match MIDI To selection in your track)
Effects-A1 Assign -> CC 07
Effects-A2 Assign -> CC 08
Effects-A3 Assign -> CC 09
Effects-A4 Assign -> CC 10
Effects-B1 Assign-> CC 11
Effects-B2 Assign -> CC 12
Effects-B3 Assign -> CC 13
Effects-B4 Assign -> CC 14
Video Fader Assign -> CC 15
Transition Assign -> CC 16
Transformer A Assign -> CC 17
Transformer B Assign -> CC 18
BPM/SYNC Assign -> CC 19
Transition Time Assign -> CC 20
Output Fade Assign -> CC 21
```

## Usage:
All controls should be MIDI control mappable and behave like their physical counterparts.  m4lv4 does not track the state of the mixer when you press physical controls, but will re-sync when you press a vitual control.

## Todo:
- User-selectable MIDI CC
- Improve integration with Live tracks for tab controls
- Standalone version
- learn md markup because I don't know how to newline without making a bulleted list

## Credits:
- Inspired by Cat Full of Ghosts Electronics V4/V8 device
- Created by J. Roman / circvlar rvins
