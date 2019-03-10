# Retrode2 Virtual Boy Plugin
Virtual Boy plugin for the Retrode 2. Support RAM/ROM acces. Should be working with Hyper Fighting

Based on JonY and Skaman works. I've added a 74HC4053D and a switch to make it work with Hyper Fighting. It's working with classic VB Games (Rom/Save game) but unfortunately I can't test it with Hyper Fighting (because game was a limited run and is freaking expensive.

You'll find in the depository:
- The PCB (Eagle File and Gerber Files in a .ZIP) - Yes you need to print the small part on the top.
- The STL file of the cart sled. I recommand ABS or PETG for printing material.
- The PSD file for the label. Work well with decal paper

You'll need to assemble it:
- a 74HC4053D in SOIC package
- a SPDT switch https://www.digikey.ca/product-detail/en/c-k/OS102011MS2QN1/CKN9565-ND/411602
- a right angle 1.7mm spacing row male header. You have 2x60pins to populate. I used two https://www.digikey.ca/product-detail/en/M50-3905042/952-1704-ND/2762133 to make one cart slot.
- an empty genesis cart shell.
