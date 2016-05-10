It´s been always discussed if electronic generated sound is less “realistic” than acoustically
generated sound. One of the main differences is the natural inclusion of the acoustic space
where an acoustic instrument is played in opposition of electronically generated ones. A good
technique to approach both worlds is to simulate the acoustic feeling of a closed space.

The reverberation (effect produced by the space where the sounding object is) is the sum of all
sound reflections of a single sound, that reaches a point in different moments.

To simulate this effect we pass the sound through a spring via two transducers (one in each end).
The sound will propagate and, thanks to the contraction and expansion capabilities of the spring,
a series of reflections will be generated. These are very similar to the ones that are generated
in an acoustic space.

This module's main features are:
* Two audio inputs. Both CV controlled plus slider control.
- “IN1” is routed both to “DRY” mix and reverb tank input.
- “IN2” Goes only to the reverb tank.
* Two outputs
- “WET” comes straight from reverb tank.
- “MIX” is the mix of DRY signal and the output of reverb tank. It has CV control

This configuration allows to feedback “WET” signal back to the module via “IN2” either through
a straight feedback or passing through other modules before coming back to IN2.

Like this, with MIX control we never loose our original signal, controlling the amount
of reverb and feedback on the mix.

It features a high pass filter at the input of the tank to control the tone of the
reverberations and an eventual saturation of the spring when we are doing a feedback.

There is a built-in Vu-meter at “WET” output to visualize level and eventual saturation of
the signal.

Block diagram:
![Block diagram](http://befaco.org/img/Modulos/Spring_Reverb_V2.5/Diagram_Reverb.png)
