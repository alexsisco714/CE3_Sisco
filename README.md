CE3_Sisco
=========

elevator controls

#Moore Machine Waveform
![alt text](https://raw.github.com/alexsisco714/CE3_Sisco/master/Moore_waveform_screenshot.JPG "Moore Simulated Waveform")

##Analysis
This waveform is correct because it starts at the first floor(0001) and moves up to the fourth floor(0100) stopping at each floor for 
at least 2 clock cycles(10ns). It then goes back down to the first floor from the fourth floor without stopping.

#Mealy Machine Waveform
![alt text](https://raw.github.com/alexsisco714/CE3_Sisco/master/Mealy_waveform_screenshot.JPG "Mealy Simulated Waveform")

##Analysis
This waveform is correct because it functions exactly like the moore machine waveform with the only exception that it displays
the next floor in a binary output.
