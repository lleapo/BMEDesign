# BMEDesign
---
__Needs Statement__

- A portable scanner to measure sensor fluorescence decay rates in patients with implanted sensors in to order provide medical practitioners with real time oxygen tissue saturation levels. 

__Design specifications__
- 	Emits light at specific wavelength- red LED at ~630 nm
-	Emits different intensities of light 
-	Adjusts time for data acquisition
-	Collects data on the fluorescence decay rate using photodetector 
-	Has separate light to indicate if sensor is present 
-	Has transistor to tell body temperature 
-	Has microUSB port to connect to DAQ system
-	Most components will be connected to a printed circuit board 
-	Casing made from 3D printed material 
-	DAQ system to connect to LabView 
-	Lab View program should: 

    + Ask for patient information/history 
    - Have somewhere to adjust acquisition time and intensity of light 
    - Graph fluorescence intensity 
    - Graph fluorescence decay time 
    - Graph temperature 
    - Calculate of oxygen saturation using decay time 
    - Graph oxygen saturation

__Constraints__
-	$9000 budget 
-	Easily reproducible 
-	Relatively small in size- around 2 by 2 inches 
-	Contains no biologically harmful substances 
-	Portable 
-	Software needs to be easily understood by someone who is untrained
