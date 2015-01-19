## Preliminary Z18 Test Data
Our lab has been running experiments with filament placement and software configuration in order to optimize our printing process for certain types of models (large, geometrically complex, mostly cylindrical) on the MakerBot Z18. 

### Machine Details
* Printer = MakerBot Z18
* Filament = MakerBot PLA Transparent Green
* We added a small mineral oil attachment to help with under-extrusion

### MakerBot Desktop
* These tests were prepared using version 3.4148 on a Mac
* Model: 20mm test cube

Cube | Extruder Temp | Chamber Temp | Feed | Oil | Result
---- | ------------- | ------------ | ---- | --- | ------
Test 1 <br /> Shells - 4 Infill 20 | 230° | 35° | Bottom | Yes | Clean. Some pull on corners. Raft bad. 
Test 2 <br /> Shells - 2 Infill 10 | 215° | 35° | Bottom | Yes | Clean. Some pull on corners. Raft bad. Corners worse than test 1.
Test 3 <br /> Shells - 2 Infill 10 | 215° | 30° | Bottom | Yes | Clean. Some pull on corners. Raft bad. Corners worse than test 1. 
Test 4 <br /> Shells - 2 Infill 10 | 230° | 45° | Bottom | Yes | Clean. Less pull on corners. Raft terrible.
Test 5 <br /> Shells - 3 Infill 10 | 215° | 35° | Bottom | Yes | Clean. Less pull on corners. Some raft issues.
Test 6 <br /> Shells - 3 Infill 10 | 230° | 45° | Bottom | Yes | Clean. Heavily deformed.

* Raft issues remain prevalent through all prints. Starting corner on all prints experienced heavy scarring. 

### Simplify3D
* We'll add data from Simplify3D tests when we have a chance...

### Details on our Profiles
* z18_low_hightemp

We've found that 215° is often too low for certain models that we print. This profile assumes that you are directly top loading from an external feed source. More details to come...

