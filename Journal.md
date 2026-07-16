# Journal
## July 8, 2026
### 8:00
Today I defined the specs for the project which is going to be a 65 percent keyboard with optical Gateron KS-22 Blacks, it will have a rotary encoder as well as a sliding pot for volume control, it will be wired and use Vial for firmware and have per-key RGB and use an RP2040. It will have PBT DSA keycaps and it will have an OLED screen on it, it is wired through USB-C, and I created the GitHub repo.
### 11:00
Decided to swap to hall effect for more wide support and custom actuation points. I decided to swap to Gateron Jade Pro (ks20) with PBT MT3 keycaps for a nice thocky sound. and I will have a vibration motor to allow for key press feedback and now using a RP2350 for better performance 
## Jul 9
### 11:20
I decided to move to a STM32F405RGT6 for better performance and better firmware compatibility.
### 11:40
I decided to move back to the RP2350 due to community support for the chips and better documentations.
### 16:21
I finished designing the first verion of the schematic and made a basic pcb with all the multiplexers having their buttons grouped with them.
## Jul 10
### 10:00
I refactored the repository so that everything is organised nicely and in its own folder.
### 11:00 - 19:00
I went through and configured the pcb as well as routing and started working on the case in onshape.
## Jul 12
### 11:00 - 17:00
I moved over to using the hardware design schematic for the RP2350b's minimalist schematic to make sure that the chip would boot instead of anyways trying to copy each component by hand. I also rerouted and placed everything on the pcb so that now everything is better routed.
## Jul 14
### 10:00 - 17:00
I worked on the case. I also added a few more mounting holes for the case. I also got the quote for the rough case outline and it would cost 117 USD for the case before shipping I also got the quote for the pcb and it would be 143 usd for just the pcb and 217 usd for the pcba maiking it 430 usd after shipping.
## Jul 15
### 11:00
I refined the pcb overall and made it a bit better and made sure to check over everything as well as moving all +3.3v nets to the +3v3 net. I also decided to remove the haptic feedback idea as that just overcomplicates things.
### 13:00 - 15:00
I reduced the size of the case so that it only weighs about 1kg now and I also made it so that it cost 80 usd instead of 127 as before, I made a blender file with all the parts and added a procedural texture for the aluminum. I also added a usb c cutout in the aluminum. I also added a threads drawing so that they will know where the threads go instead of guessing.
## Jul 16
### 10:00 - 15:00
I made the case sizing be appropriate and made the wood part of the case in onshape, I added both of those to the repo. I also refined the sizing of the pcb and moved the rotary encoder to a better spot. I added the ec11 rotary encoder as well as a knob for it to the blender file. I added the ssd1306 0.91 inch display to the blender file as well as a knob for the pta6043 as I couldnt find a model for the actual sliding pot. I also rendered a somewhat finilazed version of the keyboard and added it to the images folder as well as replacing the ai one in the readme
