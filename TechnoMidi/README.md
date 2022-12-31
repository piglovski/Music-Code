# TechnoMidi

This Python script generates a simple electronic music track using the midiutil library. The track consists of a chord progression, a melody, and a drum pattern. The tempo and durations of each element are generated randomly within a given range.

# Usage
To use this script, simply run it using Python. The generated MIDI file will be saved as output.mid in the same directory as the script.

# Customization
You can customize the script by modifying the following variables:

tempo: The tempo of the track, in beats per minute (BPM). The default value is a random float between 120 and 170.
chords: The chord progression of the track, as a list of lists of MIDI pitches. The default value is a list of four major and minor chords.
melody: The melody of the track, as a list of MIDI pitches. The default value is a list of eight ascending pitches.
drum_pattern: The drum pattern of the track, as a list of strings. The default value is a basic kick-snare pattern.
You can also add additional elements to the track, such as an atmospheric pad sound, by using the addNote method of the MIDIFile object.

# Dependencies
This script requires the midiutil library. To install it, run pip install midiutil in your terminal.
