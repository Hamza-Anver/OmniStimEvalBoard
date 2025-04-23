# OmniStim Eval Board
## Sub Modules
For ease of development different aspects of the design have been split into multiple GitHub Repositories. This monorepo may not be updated will the latest commits, please use the links below for respective aspects of the project

KiCAD Project files for the hardware of the OmniStim EvalBoard
[OmniStimEvalBoard-Hardware](https://github.com/Hamza-Anver/OmniStimEvalBoard-Hardware)

Source files for the web based controller for the PCB, uses [NiceGUI](https://nicegui.io/)
[OmniStimEvalBoard-Controller](https://github.com/Hamza-Anver/OmniStimEvalBoard-Controller)



This is an evaluation board to test operating principles of the OmniStim head unit.

Fabricated with JLCPCB in April 2025, designed with KiCAD.

It is designed to use the ESP32 Audio PLL to create a signal between approximately 5MHz to 80MHz. This signal is then conditioned and used to drive an LC tank, where the capacitance can be varied digitally and by the DIP switches.

Future designs will have their capacitance entirely digitally controlled, and be miniaturized.

This board is intended only to test if the ESP32 with this conditioning can successfully drive the LC tank and if the resonance of the tank can be subsequently measured by the ESP32.


