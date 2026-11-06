Helloooo this is last week of design for hack life, and I'm doing a split keyboard!
Ever since I learned about being able to do one from Hack club, I've been looking for opportunities to. Now that I got one, hopefully I have enough free time to do it. I feel bad about not doing my college apps and my tons of hw...

Schematic!
<img width="828" height="584" alt="image" src="https://github.com/user-attachments/assets/f40da116-0598-4730-9386-ccaf6d19cd78" />
The labels are kind of scuffed. I pretty much made a matrix of 25 keys, using as much as possible, and customized where the pins pointed to so it was easier to route on the pcb. 

PCB!
<img width="422" height="642" alt="image" src="https://github.com/user-attachments/assets/ec36aa4f-d713-4403-9d5d-7b3917a12857" />
This took so so long. So currently, most of the letter keys are assembled in a staggered format, similar to a regular keyboard. This is to retain muscle memory for typing and gaming. The ctrl button the left side and space button on the right are still within the 5x5 matrix for the pins, but are one row down for muscle memory.

Code!
<img width="1477" height="872" alt="image" src="https://github.com/user-attachments/assets/1dd92e0d-1795-4ebf-bfb2-fc57ec4e99be" />
I had to create a custom keyboard module using zmk. I learned and implemented making new shields for each side, setting ids, doing soft-off power management, and doing keymaps. In the keymaps, mod-morphs, macros, hold-taps, and regular kps were used to give more complex, unique functionalities. This way, it isn't one/two outputs for each press, but potentially 3/4 depending on which layer (gaming or default) is toggled and the combination of keys pressed. 
I also made sure to write my configs down for future reference and to make sure I don't forget over the few days I do this project.
<img width="575" height="399" alt="image" src="https://github.com/user-attachments/assets/62e37cbc-b937-42ed-9540-f1ab67a13095" />


CAD!


BOM!

Only after making the hardware did I realized just how much it costs, even with Aliexpress and the 11.11 deals (hopefully I can get this approved by then). The microcontrollers and custom pcb cost the most, but that is to be expected. Just once added together, it accumulated to a lot. I think I can get enough hours for the tier 3 funding though.

