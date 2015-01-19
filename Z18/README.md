## Preliminary Z18 Test Data
Our lab has been running experiments with filament placement and software configuration in order to optimize our printing process for certain types of models (large, geometrically complex, mostly cylindrical) on the MakerBot Z18. 

### Machine Details
* Printer = MakerBot Z18
* Filament = MakerBot PLA Transparent Green
* We added a small mineral oil attachment to help with under-extrusion

### MakerBot Desktop
* These tests were prepared using version 3.4148 on a Mac
* Model: 20mm test cube

Test | Shells | Infill | Extruder Temp | Chamber Temp | Feed | Oil | Result
---- | ------ | ------ | ------------- | ------------ | ---- | --- | ------
T1 | 4 | 20 | 230° | 35° | Bottom | Yes | Clean. Some pull on corners. Raft bad. 
T2 | 2 | 10 | 215° | 35° | Bottom | Yes | Clean. Some pull on corners. Raft bad. Corners worse than test 1.
T3 | 2 | 10 | 215° | 30° | Bottom | Yes | Clean. Some pull on corners. Raft bad. Corners worse than test 1. 
T4 | 2 | 10 | 230° | 45° | Bottom | Yes | Clean. Less pull on corners. Raft terrible.
T5 | 3 | 10 | 215° | 35° | Bottom | Yes | Clean. Less pull on corners. Some raft issues.
T6 | 3 | 10 | 230° | 45° | Bottom | Yes | Clean. Heavily deformed.

* Raft issues remain prevalent through all prints. Starting corner on all prints experienced heavy scarring. 

### Simplify3D
* We'll add data from Simplify3D tests when we have a chance...

### Details on our Profiles
* z18_low_hightemp

We've found that 215° is often too low for certain models that we print. This profile assumes that you are directly top loading from an external feed source. More details to come...

