First big schoolproject : SolderStation that is powered bij a battery(makita 18V)

In the files you can find all the schematics of the main board. There is a connection for a makita battery what can connect directly on makita 644808-8 terminal.


the display is external and is powered by a cable between display PCB and main PCB. 

the GX12 pin for soldering is wired as follows : 
-  Pin1 power from common mode choke CM2545X171B-10
-  Pin2 ground from common mode choke CM2545X171B-10
-  Pin3 output OP-AMP for temperature 
-  Pin4 connected to ground 

There are some issues in the schematics that needs to be fixed. 
The OP-AMP MCP6002-I/P VSS(pin4) and VCC(pin8)  are switched this is fixed in the schematics but not on PCB
The C-pin  of the rotary encoder PEC11R-4220F-S0012  switch is nog connected to gorund. Fixed on schematic but not on PCB

