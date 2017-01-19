Reverb-delay with stereo output, settings allow to make sounds from subtle reverberation to huge echoes and everything in between.

- Predelay : early reflections of the sound, it determines the size of the room (10 to 100 ms)

- Reverbtime : subsequent delays coming from the early reflections delay line (20 to 500 ms), set at high value to get an echo effect, low value for a reverb-like type of sound

- Damping : filters the sound inside the delay lines, affects fading time too

- Regeneration : feedback of signal inside the delay lines, make the effect last longer

- Wet : the amount of reverb/delay mix with the input sound

- Output volume : output volume


Midi-learn

- toggle midi-learn and move knobs to assign them to every parameters (check pd console), assignment is saved in an array with the patch
- audio input is from sound card channel 1 or inlet~ if used as an abstraction
- stereo audio output