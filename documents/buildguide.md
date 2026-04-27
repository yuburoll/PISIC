# Build Guide
this is build guide for PISIC.

This documents is translated by generative AI, so there can be some misleading texts.

### Additional Resources
[**Soldering Tips**](solderingTip.md)

# PCB Preparation
Prepare two PCBs for the PISIC. Since these are reversible PCBs, be careful to place components on different sides for each board.

The side where components will be placed is treated as the back, and the side without components is treated as the front. **All components go on back side only, so please be careful when soldering.**
![pisicPhotoPCB0](../images/pisicPhotoPCB0.jpg)
![pisicPhotoPCB1](../images/pisicPhotoPCB1.jpg)

# Soldering the Diodes
Solder the diodes. The photos show SMD diodes being used, but THT diodes can also be used.

When using SMD diodes, first apply a solder blob to one side of the pad with a soldering iron, as shown in the following photo.
![pisicPhotoDiode0](../images/pisicPhotoDiode0.jpg)

Reheat the solder blob with the iron to melt it, align the diode in the correct orientation and place it in position, then remove the iron.
![pisicPhotoDiode1](../images/pisicPhotoDiode1.jpg)

Once it is seated properly, solder the opposite leg.
![pisicPhotoDiode2](../images/pisicPhotoDiode2.jpg)

# (Optional) Soldering the LEDs
Solder the underglow LEDs. The process is largely the same as soldering SMD diodes, but extra care is needed when applying heat.

First, apply a solder blob to one side of the pad with a soldering iron, as shown in the following photo.
![pisicPhotoLED0](../images/pisicPhotoLED0.jpg)

Reheat the solder blob with the iron to melt it, align the LED in the correct orientation and place it in position, then remove the iron.
![pisicPhotoLED1](../images/pisicPhotoLED1.jpg)

Once it is seated properly, carefully solder the remaining three pads. Note that solder may not flow into them easily, so take care.
![pisicPhotoLED2](../images/pisicPhotoLED2.jpg)

# Soldering the Hot-swap Sockets
Solder the hot-swap sockets. The process is largely the same as soldering the diodes and LEDs.

As before, apply a solder blob to one side of the pad, reheat the blob to melt it, place the component and hold it in position, remove the iron, then solder the opposite leg.
![pisicPhotoHotswap0](../images/pisicPhotoHotswap0.jpg)
![pisicPhotoHotswap1](../images/pisicPhotoHotswap1.jpg)

# Soldering the TRRS Jack
Refer to the following photos to identify where the TRRS jack will be placed.
![pisicPhotoJack0](../images/pisicPhotoJack0.jpg)
![pisicPhotoJack1](../images/pisicPhotoJack1.jpg)

Solder the TRRS jack. When soldering the Tip and Sleeve pins, also bridge them to the adjacent pads as shown in the photo.
![pisicPhotoJack2](../images/pisicPhotoJack2.jpg)

# Soldering the Dev Board
First, check the header pins on the provided Pro Micro dev board. The outermost row of header pins past 5V is not needed, so trim them off.
![pisicPhotoDevboard0](../images/pisicPhotoDevboard0.jpg)
![pisicPhotoDevboard1](../images/pisicPhotoDevboard1.jpg)

Insert the header pins starting from 5V, align them, and solder the dev board. When soldering, make sure the components face upward as shown in the photo.
![pisicPhotoDevboard2](../images/pisicPhotoDevboard2.jpg)
![pisicPhotoDevboard3](../images/pisicPhotoDevboard3.jpg)

Place the dev board with the freshly soldered header pins on top of the already-soldered hot-swap sockets. Press down firmly to ensure a snug fit.
![pisicPhotoDevboard4](../images/pisicPhotoDevboard4.jpg)
![pisicPhotoDevboard5](../images/pisicPhotoDevboard5.jpg)

Just like when soldering the TRRS jack pins, bridge the header pins to the adjacent pads as if creating jumpers. Since a large amount of solder is used, there is a risk of bridging, so be sure to clean the area with alcohol after soldering.
![pisicPhotoDevboard6](../images/pisicPhotoDevboard6.jpg)

# Soldering the Jumpers
On the front side seen when soldering the dev board, bridge the jumpers located just below. Apply enough solder so that a blob forms on top.
![pisicPhotoJumper0](../images/pisicPhotoJumper0.jpg)
![pisicPhotoJumper1](../images/pisicPhotoJumper1.jpg)

# Assembly
First, assemble the case, plate, and switches together. (Note: If you assemble the plate, switches, and PCB first, the assembly will not fit into the case.)
The plate and case are fastened together with screws at four points.
![pisicPhotoAssembly0](../images/pisicPhotoAssembly0.jpg)
![pisicPhotoAssembly1](../images/pisicPhotoAssembly1.jpg)

Insert the protruding part of the TRRS jack into the hole in the case, then lower the PCB onto the switches to mate them together.
![pisicPhotoAssembly2](../images/pisicPhotoAssembly2.jpg)
![pisicPhotoAssembly3](../images/pisicPhotoAssembly3.jpg)

Place the backplate over the case and fasten it with screws at eight points per side to complete the build.
![pisicPhotoAssembly4](../images/pisicPhotoAssembly4.jpg)