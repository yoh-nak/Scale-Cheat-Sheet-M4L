# Scale Cheat Sheet for Ableton Live

**Scale Cheat Sheet v1.0** is a free Max for Live music theory reference device for exploring, visualizing, comparing and learning musical scales directly inside Ableton Live.

It provides interactive piano keyboards, guitar fretboards and bass fretboards with support for different tunings, extended-range instruments and octave-aware note highlighting.

The device is designed as a music theory reference, not a MIDI generator or instrument.

## Features

### Scale Library

- 112 scale entries covering 99 distinct interval structures
- Major, Minor, Modes, Pentatonic, Blues, Jazz, Bebop, Symmetrical and World scales
- Search by scale name or alternative name
- Genre and category filtering
- All 12 chromatic roots
- NOTE, DEGREE and BOTH display modes
- Scale intervals, semitone structures and related information

### Interactive Instrument Displays

- Piano, Guitar, Bass and ALL display modes
- Guitar and bass support for 3–12 strings
- Standard, alternate and custom tunings
- Up to 24 frets
- Fit-to-window and scrollable fretboard display
- Automatic piano keyboard range adjustment
- Full 88-key keyboard option
- Adjustable interface text and note-label sizes
- Interactive note selection across instruments

### Note Highlighting

Click a note on any instrument display to highlight matching pitches throughout the other instrument displays.

- Green — exact same MIDI pitch
- Purple — same pitch class in another octave
- Orange — scale root
- Blue — other scale tones

This makes it easy to understand where the same notes appear across piano, guitar and bass.

### Similar Scales

The Similar Scales feature helps you learn new scales by comparing them with familiar ones.

- Automatically discover scales with similar note structures
- Find scales differing by only a few notes
- Compare common and different scale tones
- Filter by the number of changed notes
- Compare note names and scale degrees
- Display simple learning hints
- Jump directly to related scales

For example, C Major and C Lydian share six notes. Changing F to F# transforms C Major into C Lydian.

This approach helps you memorize scales through their relationships rather than learning every scale independently.

## Installation

1. Download `Scale_Cheat_Sheet_v1.0.amxd` from this repository or its Releases section.
2. Open Ableton Live with Max for Live support.
3. Load an instrument onto a MIDI track.
4. Place Scale Cheat Sheet **after the instrument** in the device chain.
5. Click **OPEN SCALE CHEAT SHEET** to open the main reference window.

Scale Cheat Sheet is implemented as a Max for Live Audio Effect with stereo audio pass-through.

It does not generate sound and is intended for visual reference.

## How to Use

1. Select a root note.
2. Search for a scale or choose one from the library.
3. Filter scales by genre or category if needed.
4. Switch between piano, guitar, bass or all instrument views.
5. Select NOTE, DEGREE or BOTH to change note labels.
6. Adjust the number of strings and tuning for guitar or bass.
7. Click a note to highlight matching pitches across instruments.
8. Explore Similar Scales to discover closely related scale structures.

## Scale Naming

Some scales have multiple established names. Alternative names are supported in the search system.

Selected traditional and world music scales are represented using 12-tone equal-tempered approximations and may not reproduce all characteristics of their original musical traditions.

## Compatibility

- Max for Live Audio Effect
- Developed for Ableton Live 12
- Windows 11 development environment
- Max for Live required
- Single `.amxd` file
- No external dependencies

Other operating systems and Ableton Live versions have not been fully tested.

## Modification and Redistribution

This device is free to use.

You are welcome to open, study and modify the Max for Live device, including its interface, scale library and internal functionality.

You may also share your modified versions for free.

Please do not sell the original device or modified versions.

This project is intended for free community use, learning and experimentation.

## Feedback and Contributions

Suggestions, bug reports, corrections to scale definitions and requests for additional features are welcome.

You are also welcome to create your own variations of this device.

## Author

Created by **yohsukenak**

GitHub: https://github.com/yoh-nak

**Free Max for Live devices for music production, MIDI processing and music theory.**
