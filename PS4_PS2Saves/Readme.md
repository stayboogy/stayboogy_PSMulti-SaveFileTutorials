# PS2 Saves for FPKG Games for PS4 GoldHen 11.00

## How to convert PS2 Saves from various formats to work for PS4 FPKG Games

### Windows Directions

#### Install python + pip

https://pip.pypa.io/en/stable/installation/

#### Install mymcplus

https://sr.ht/~thestr4ng3r/mymcplus/
```sh
pip install mymcplus[gui]
```

1) create formatted ps2 card with mymcplus: 

mymcplus -i empty.ps2 format

2) run mymcplus:

mymcplus

3) open empty.ps2 card from step 1 and exit

4) a) export your actual ps2 virtual memory card from your ps3 / export your ps2 saves from your ps2 /
export your saves from your ps2 emulator / export your .vm2 card / export your .ps2 card into .max or .psu format using whatever tool you like 

   b) but I take my raw save folders from my actual ps2 memory card, open ps2 save builder and import the raw files individually for one certain game, save that as a .max savefile, then import that save into mymcplus, then export that save to .psu format
   
5) open empty.ps2 card from step 1 and import your .psu save from step 4 for a single specific game and then exit

```sh
single game raw save folder > ps2-save-builder > export to .max savefile > import .max savefile to mymcplus > export to .psu from mymcplus > import .psu to empty.ps2 card with mymcplus
```

6) rename empty.ps2 to game-name.ps2

7) use game-name.ps2 card for memory card using ps2-fpkgv0.6 only