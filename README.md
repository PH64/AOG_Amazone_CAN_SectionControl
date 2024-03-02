# AOG_Amazone_CAN_SectionControl
SectionControl based on CAN Messages for AgOpen GPS and Amazone machines by Alexb933 and Valentin.

The sketches are based on the Machine_USB_v5 Sketch from AGO... 
Also an excel file which explains the CAN Message structure.

You can use only AMATRON, or with AMACLICK and also with Joystick at the same time. Be careful when you use AMACLICK in AUtosection Mode -> turn off AMACLICK or remove it.
Attention: when using the CANBUS shield and the optional physical switch -> PIN 2,9,19,17 are not available

Be careful when using CANBUS (use the right Pins and do not current them!). Use at your own risk. I tested the code but no guarantee for none complications
At the moment November 2023 the "marking mode" (Sketch 1) only supports until 7 Sections because the CAN Code for upper sections is unknown.
Please feel free to change the code or adapt to your situation.

Precisions for Amatron 3 et 4 isobus:   
AOG control sections with Amatron 3 and 4 in manual mode ou automatic mode.   
- in "Machine_USB_v5_CAN_AMATRON_SectionControl", section control works only on AOG,  
- in "Machine_USB_v5_CAN_AMATRON", button pressed, section control works only on AOG, button unpressed, amatron 3 or 4 controls the sections but AOG does not retrieve the marking information

Thanks to Alexb933 and Valentin for the code
