A low cost hobbyist grade, constant power and constant current electronic dummy load.

The FreeLoad is born out of nessecity, I was in search of a dummy load design that would allow me to test the robustness of a home built battery pack and managment solution. Many simple constatnt current load disgns esist already, but very few constant power load exist that use an analog control loop. Though a microcontroler can make the process of creating a constant power load ismple, it ads unessecary cost and complexity to what should be a very simple circuit.

The FreeLoad is robust and has no processor to lock up.
The FreeLoad is linear, a typical solution to create a constant power load is to attach a load to a switching boost converter. By using MOSFETs to dissipate power the FreeLoad appears as a purely resistive load to the source. This eliminates artifacts or strange behavior caused by switching noise.
The Freeload uses $50 in parts (excl. heatsink and PCB.) The FreeLoad is easily scaled up to dissipate more power, or down to dissipate less power.
------------------------------------------------------------------------------------------------------------------------
Future additions:  
Constant ressitance mode  
Battery capacity measurement, with microcontroller control and low voltage cuttoff.   
Coarse and fine adjustment knobs.  
BNC input for current setting.  
High speed load switching to detect power supply output ringing.
  
1/4/17:  
Naming convention established:  

For entire assemblies:  
A.B.C.D.E  
RA: Release number 
FB: Featureset number 
SC: Schematic revision  
BD: Board revision  
OE: Overall device revision   

*Release numbers are only to be changed when a completed product is released, featureset, 
scheamtic revision, board revision, and overall device revision numbers may be changed 
until the relase number changes, at which point all other numbers must reset to 0.   

For board or schematic diagrams:  
A.B.XC  
A: Release that the schematic or board belongs to    
B: Featureset that the scheamtic or board belongs to  
XC: X = 'S' for schematic
	X = 'B' for board.  
	C = individual schematic or board revision number.      
Simulation files will be titled as "FreeLoad_X"  where X is replaced with the accompanying schematic revision. 

FreeLoad 1.0 now becomes FreeLoad R1.F1.S2.B1.O1    
FreeLoad 1.2 now becomes FreeLoad R1.F2.S3.B2.O2
  
Each complete release of the device will also have a codename:  
Release #:  Codename:  
	1		Wachusett
	2		Haskell
	3		Lyman
More release numbers and codenames may be added as needed  

When a release is finalized and ready for sale it will be accompanied by a simple name:
"FreeLoad X"  
Where 'X' is the release number in Roman numerals.  For revision 1 the I will be omitted and the name will only be "FreeLoad".  
