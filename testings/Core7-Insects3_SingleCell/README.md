# Single Cell Biomass Harvest

This test was designed to demonstrate whether partial mortality (from insects) and material left on site reflected intentions.

Demonstration outputs:
Biomass-succession-log-test_conclusion.csv
insect-log-test_conclusion.csv
Landis-log-test_conclusion.txt

Some notes:
* IMPORTANT:  In this test, partialDisturbance.cs line 159:  I hard-coded in a value for percent mortality.  This is because at a single cell, it was difficult to create insect mortality.  Also, I don't really understand the parameters.
* Wood decay was turned off.  This is because it is difficult to observe wood accumulating from partial mortality if it is simultaneously decaying.  The amount of wood being added is less than the total partial mortality because a percentage is leaf material (litter).
* I could not turn off leaf decay and so it increases and decreases according to both partial mortality and decay.  It was not possible to isolate this process.
* The landis-log text file shows the outputs from both extensions.  Biomass succession outputs can be turned off using CalibrateMode.  Biomass insect outputs are hardcoded and need to be commented out.
