# DSP-Project
Transmits a digital image file through a discreet EM wave. The receiver then reconstructs image file based on modulated discreet wave values.

The program takes frequency and modulation values as input to create a discrete carrier wave. The program also takes a digital image file. The program converts the image file to binary values and uses them to amplitude modulate the discreet carrier wave for transmitting. The receiveing end of the program takes the modulated amplitude values and compares them to a generated carrier wave of the same frequency and amplitude as the transmitter. The program then converts the discreet wave values to binary and writes those values to an image file thus re creating the image that was transmitted transmitted.  
