# The schtick

The schtick is a mini game controller for your laptop, with some emphasis on flight sims. It is the byproduct of the larger Viper cockpit project, after a few parts were left over. And born on a vacation where I really missed my DCS world setup and realised I could do some leisure flying on my laptop...

The whole thing fits in a box 180x180x50mm, and contains:

* Two mini joysticks (think X-box pads), where one is modded to be usable as a throttle. One standard stick on left, and throttle/rudder on right is the intention
* 8 encoders
* 4 pots
* 8 push buttons (next to the sticks)
* 16 toggle switches (with two button functions each)

Everything is controlled by a Teensy 3.2 - using one 6x6 matrix for toggles and pushbuttons, digital inputs for encoders, analog inputs for pots.  It uses the same PCBs as the viper cockpit.

It is possible to swap out the encoders for latching switches, so separate code for this is provided.

The whole box is built out of 4mm acrylic glass, painted up nice with color coded panels.

()[https://raw.githubusercontent.com/krorvik/schtick/master/images/schtick.png]
