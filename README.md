# Radioberry_MIDI
Midi controller for Radioberry, with filter selection (N2ADR open collector emulation)

install:

Put your RP2040 in programming mode (push RP2040 button and connect to USB on your computer, 
when the files manager opens, release button)

Copy the .uf2 file to the RP2040 using the file manager opened by RP2040.

When the file is uploaded, the green led on the RP2040 blinks.

testing:

install the MidiView on your pc and select the RP2040 midi device, you can see the encoders, 
buttons and pot Midi dialog.

you can download midiview from this page for free: https://hautetechnique.com/midi/midiview/

On the Radioberry piHPSDR, you need to configure the open collector outputs, in the menu 
as you can see on the open collector.JPG file in order to enable the band decoder, remember 
the outout are bcd coded as for Yaesu band data spaecifications.

On the midi configuration, you can select any configuration you want for the midi. In my case 
- one encoder is VFO
- one encoder is drive
- one pot is volume control
- one pot is mic gain control
- one button is mic UP pushbutton  
- one button is mic DOWN pushbutton
- one button is band UP
- one button is band DOWN
- two button already not assigned
- VFO encoder button pulsed, step are 500 hz, released step are 50 hz 
