## Contribution Guide
Your new patches should go into the "workinprogress" folder. After all of the Pd Patching Guide for pisound requirements are met we will test the patches and move them to the "readytogo" folder.

If you are looking for ideas for new patches, you can take a look at the "watinginline" folder and pick some patches to port from there. In that case don't forget to move them into the "workinprogress" folder.

That’s it. Happy patching! 

## Pd Patching Guide for pisound

- Patches should be made with Pd-vanilla, preferably using version 0.46.2, as found on raspbian apt-get, without the use of additional libraries or externals;
- It should be possible to use patches without a screen or mouse - all controls mapped to MIDI messages and we highly suggest to include MIDI learn functionality.
- Patches can be made from scratch or adapted from other sources but only if the patch licence allows it;
- Patches should be provided with screenshot, audio sample file (depending on patch specifics) and README.txt with short description and list of MIDI messages with corresponding parameter names;
- Every variable name should start with $ sign to prevent possible conflicts when using multiple instances of the same patch;
- The main patch file should be called main.pd and consist of adc~, dac~ (depending on patch specifics) and main abstraction canvas containing patch controls;
- No combination of parameter values should result in clipping;
