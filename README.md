# Voltage_Regulators

## How to import the Regulator files into a Diptrace Project

To use either of the voltage regulators within a project first download the desired voltage regulator file.  This is a hierarchy block file that when opened will open the desired voltage regulator in another sheet within a project.  Then on another sheet select: Object -> Hierarchy -> Place Block.  Then select the voltage regulator block that was just downloaded and opened within the project.  Now the block will be able to be used within the project with the appropriate inputs and outputs labeled.



## Fixed 5 Volt Regulator

This circuit utilizes the LM109H single silicon chip that is capable of outputting a 5-volt constant output regulating the input voltage.
C1, the first capacitor, is used to help filter the input and remove excess noise from within the circuit before the voltage enters the LM109H.
C2, the second capacitor, is used to help improve the transient response of the output voltage to make the circuit respond faster when voltage is first input.
One feature of this chip is the ability to output a current that is around 1 Amp providing varied applications for this voltage regulator.

Parts List:
   
    (U1) LM109H
    (C1) 1uF Capacitor
    (C2) 2uF Capacitor
    
Note: C2 can be any value above 1uF as it is used to improve the transient response of the output voltage.
Select the best value that fits the transient response need.
    
## Adustable Voltage Regulator
      

Parts List:
    
    (U2) LM317LZ 
    (C3) 0.1uF Capacitor
    (C4) 10uF Capacitor
    (C5) 1uF Capacitor
    (D1) 1N4001 Diode
    (D2) 1N4001 Diode
    (R1) 240 Ohm Resistor
    (R2) 5K Ohm Variable Resistor
    
