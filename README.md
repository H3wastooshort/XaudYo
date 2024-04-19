# XaudYo
An online YX-Oscilloscope / Vectorscope in JavaScript, running in your webbrowser.
Audio Files, Microphone Input, and Desktop Audio are supported.

## Parameters
### Mode
Choose between Files, Microphone and Desktop. Switch to File and back to select a different Window/Microphone.

 * Large files seem to be a bit buggy on firefox.
 * Audio capture seems to only be supported on Chromium based browsers for now :(
 * To capture desktop audio on Firefox, use the "Stereo Mix" or "What-U-Hear" loopback microphone if your audio drivers support that.
### Sampling Time
How many samples of audio to display at once. Play around wit this to get the best image.
### Gain
How "zoomed in" the image is. Louder = Bigger, so more gain = bigger.
### Swap Channels
Check this if the image seems to be rotated 90°. (useful for oscilloscope music)
### Phosphor Decay
Simulate the afterglow of an analog scope's phosphor screen.
### Scale
Add a Pattern to the scope. Not very useful...
### Playback Volume
self explanitory.
