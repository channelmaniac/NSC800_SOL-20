# NSC800_SOL-20
NSC800 CPU adapter for a SOL-200 Computer

I've been entrusted with 2 SOL-20 computers to restore, one of which came with an NSC800 CPU on a homebrew wire wrapped board. This CPU is fully compatible with the Z80 instruction set and upgrades the SOL-20 from an 8080A to a Z80 compatible S100 bus computer.

I could not find any reference to using an NSC800 on the SOL-20 so I spent some time with a multimeter reverse engineering the board.

Here you will find the board schematics and a picture of the homebrew with labels on the 4 contact points where it plugs into the computer's main logic board.

I have not laid out a PCB for this yet as it would take a bit of time to line up the headers that plug into the sockets on the main logic board. Feel free to layout a PCB and I'll link to it from here.

![NSC800 Adapter](https://github.com/user-attachments/assets/151ad04c-4c97-4fc0-976c-b6c6e142ba04)

It uses the following components:
* NSC800 CPU
* 1M Resistor
* 10pf Capacitor
* 47pf Capacitor
* 2x 74LS04
* 74LS08
* 74LS74
* 74LS138
* 74HC373
* Headers or wire wrap sockets with long legs to plug module into sockets on the SOL-20's motherboard
