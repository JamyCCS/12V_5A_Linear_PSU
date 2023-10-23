# 12V_5A_Linear_PSU
A simple Linear PSU circuit with constant 12V output and max 5A current draw. 

***CAUTION ON DEALING WITH HIGH AC LINE VOLTAGE. ALWAYS MAINTAIN SAFETY PROCEDURE***

Software used: EASYEDA STD ONLINE CLIENT VERSION. JSON files are attached. You can open them via importing in EASYEDA. 

I tried to make a 12V 5A PSU. A circuit is made that will be connected to a transformer 
The transformer should have 220V 50 Hz AC to 24V AC output capabilities. 

The circuit has 2 indicator LEDs to confirm input and output current flow.

A 5 A fuse is attached to the output end to ensure a safe 5A supply. 

4 6A10 diode with 6A max current rating is used as full bridge rectifier

LM338 is used for linear voltage regulation. Reference voltage dividing is made with  suitable resistor values and diodes are added to protect the IC from backward current. 
