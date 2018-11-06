# BOLSIG-Minus
BOLSIG minus requires a text file as input. This python script writes this text file with a loop that changes the gas contents of a plasma.

The python script writes a text file with a given file name. It writes the following to this text file:

    1.the cross-sectional files to import to Bolsig
    2.the parameters of the plasma such as temperature and ionization
    3.the gas percentages of the plasma which is looping.
    4.the runseries which determines the changing ("VAR") reduced electric field
    5.how the output files of Bolsig are saved ready for analysis

This is a python script written in python 3.0. Running this will generate a text file which is the input to Bolsig minus. One must save the text file to the same folder as where Bolsig minus is saved. Cross-sections must also be saved to this same folder. Running Bolsig minus brings up a command prompt. Type the text file name and hit enter will run Bolsig minus and produce all the output files described in the text file.

The code is currently set to loop 25^3 gas contents which is over 15,000 Bolsig runs (Around 15 hours of data collection).
