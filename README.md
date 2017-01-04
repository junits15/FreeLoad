# FreeLoad
A low cost hobbyist grade, constant power and constant current electronic dummy load.

The FreeLoad is born out of nessecity, I was in search of a dummy load design that would allow me to test the robustness of a home built battery pack and managment solution.  Many simple constatnt current load disgns esist already, but very few constant power load exist that use an analog control loop.  Though a microcontroler can make the process of creating a constant power load ismple, it ads unessecary cost and complexity to what should be a very simple circuit.  

The FreeLoad is robust and has no processor to lock up.  
The FreeLoad is linear, a typical solution to create a constant power load is to attach a load to a switching boost converter.  By using MOSFETs to dissipate power the FreeLoad appears as a purely resistive load to the source.  This eliminates artifacts or strange behavior caused by switching noise.   
The Freeload uses $50 in parts (excl. heatsink and PCB.)
The FreeLoad is easily scaled up to dissipate more power, or down to dissipate less power. 


Future additions to the project may include:  
Constant ressitance mode  
Battery capacity measurement, with microcontroller control and low voltage cuttoff.   
Coarse and fine adjustment knobs.  
BNC input for current setting.  
  
Changes for schematic v1.3  and board v1.2
-BNC connections for setting and measurement  
-Switch all IC's to SOIC-8, for reduced board size and cost  
-Switch to single rail supply
-Use ADR510 for precision 1V reference instead of resistor dividers
-decrease board size by at least 25% 

Branches exist for both schematic revisions.  

