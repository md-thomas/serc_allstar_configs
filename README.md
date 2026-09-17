### README.md 

## Note
Every time you change a setting in simpleusb or the config files you need to restart astersik (astres.sh)


## Site Info
SMH-S Node 	
IP Address: 	10.166.232.76
Port: 			222
User: 			root
PW: 			
Allstar ID: 	1200
Radio/Repeater/Controller: ICOM FR-5300 

SMH-V Node 
IP Address: 	10.209.110.67
Port: 			222 
User: 			root
PW: 			
Allstar ID: 	1201
Radio Repeater/Controller: Kenwood TKR-850


### Helpful Commands 
# restart asterisk
astres.sh 

# start asterisk
astup.sh 

# stop asterisk 
astdn.sh 

# astersik command line interface 
asterisk -r 

# simpleusb tui 
simpleusb-tune-menu 


### Pinout Info
Correct Mapping: RA-35 to Icom FR5300 (HD15)
To wire an Masters Communications RA-35 interface to the Icom FR5300 DD25 connector, use this corrected pin mapping:

RA-35 Pin 6 	(RX Audio In) 		→ Icom DB25 Pin 1 	(AF OUT/RX Audio/Det Audio)
RA-35 Pin 5 	(PTT Out) 			→ Icom DB25 Pin 9 	(PTT)
RA-35 Pin 3 	(COS In) 			→ Icom DB25 Pin 25 	(Set to Busy/COR Output in CS-FR5300 software)
RA-35 Pin 1 / 2 (TX Audio Out) 		→ Icom DB25 Pin 21 	(MOD IN)
RA-35 Pin 8 	(Ground) 			→ Icom DB25 Pin 7 	(GND)



