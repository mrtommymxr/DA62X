**Key Features.**

1. **Automatic propeller control** 
Using a SimConnect module, we are able to control prop RPM based on the power output of the engine. This acts like single lever control, however its based on engine power output and not lever position. Due to a bug, we are unable to distinguish between the left an right engine. The right engine mimics the left 

2. **Engine changes** 
* Proper fuel flows 
* Changed OIL/Coolant temp and pressure behaviour
* Increased thrust scalar
* Fixed Fuel Pumps

3. **Compatibility with the Working Title G1000 mod**
* Added Engine, Systems and Fuel page
* Aux tank fuel indication added
* Added fuel/Gearbox temperature indications 
* CAS messages added  

Link:
https://forums.flightsimulator.com/t/release-working-title-g1000-v0-3-1-9-3-0-compatible/288944/27
 
4. **Flightmodel**
* Correct cruise speeds
* Reduced elevator and rudder sensitivity
* Improved Cl table and stall characteristics
* Improved inflight handling characteristics all around
* Decreased ground friction and turn radius
* Increased flap lift and drag
* Increased Gear drag

5. **Systems**
* Lowered standby instruments brightness
* Improved lighting, Added Ice light
* Anti-ice system functional 
* Improved autopilot PIDs and limitations
* Engine Indications Connected to Engine Master switches 
* Ammeter behaves correctly to alternator and engine state

And other general improvements 


**Todo:**
* Flightmodel: Correct performance all around
* Systems: Redo everything, Full G1000- FADEC integration 
* Alot more

**Issues/bugs**
* FADEC need a few seconds to initialise/might not at all. Reload and try again.
* SimConnect cant distinguish between the engine 1 and 2, so the right engine RPM mimics the left.
* Ice light is on by default


Thanks to: 
Nishmaster for the FADEC
Friends for helping me with C++
Uwajimaya for the lighting mod
Jonasbeaver for his findings on the autopilot and stuff
