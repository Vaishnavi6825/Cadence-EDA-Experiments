`EX NO 1
DESIGN AND IMPLEMENTATION OF CMOS INVERTOR USING CADENCE AND EDA TOOLS`

`AIM:`

To design and implement a CMOS inverter circuit using Cadence EDA tools, analyse its electrical characteristics, and understand the fundamental principles of CMOS technology, including the design process, layout, and simulation techniques.

`TOOLS REQUIRED:`

• Personal Computer. <br>
• Cadence Virtuoso Software.

`S C H E M A T I C S I M U L A T I O N `

PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION
`Commands to get into Cadence`

-Right Click and open the terminal window

-Type the following commands as follows and press enter. • csh • source /cadence/install/cshrc • virtuoso Procedure for Schematic simulation using Cadence

-Now two windows must open
i) virtuoso/command interpreter window 
ii)”Whats New…”

-Close the 2nd window

-Use 1st window i.e virtuoso window (CIW) for further processing.
i. Create a New Library
ii. Create Schematic Cell view. 
iii. Create the Symbol for schematic Cell view.
iv. Create the test Cell view.
v. Analog simulation by spectre

`SYMBOL`

![WhatsApp Image 2024-09-05 at 20 55 51_3587152b](https://github.com/user-attachments/assets/7ff96a52-8b43-4fe6-8648-33ab74a5d074)


i) Procedure for Creating New Library. 
• File –New – Library • Name: Give name for ur library Ex: VLSILAB_EXP_1
• Enable Attach to an existing technology library, Click OK
• Attach the library to the technology library gpdk045.Click OK 

ii) Create Schematic Cell view. • Go to 1st window i.e virtuoso (CIW) 
• File-New-Cell view 
• Setup the new file form  Library: Select the one you created.  Cell: Give the experiment name Ex: Inverter ViewSchematic  Type: Schematic press OK 
• Add the required components from the libraries and make the connections.  Go to instance fixed menu or use shortcut key “I” from keypad to go instances  Click on browse. This opens the library browser  Now select the appropriate library for components like  Gpdk45 ------------------------nmos1v, pmos1v  Create Input and Output pins  Make the connections by using fixed narrow wire key  Click Check and Save button image

iii) Creating the Symbol for schematic Cell view

• In the schematic window, execute  Create – Cell view – From Cell view  The cell view from cell view window appears  Check Lib Name, Cell Name, From View name must be schematic Press ok 
• Now Symbol generation form appears. Click Ok If No changes required 
• A new window with with default symbol is created.
• Edit the symbol if you want to give actual symbol shape else continue. 
• Execute Create-Cell view-from cell view • Library Name and Cell Name must be same which you have used for schematic. Press OK 
• Check for the position of pin side.Prss OK 
• Edit for the shape by Create-Shape-Choose required options to edit.

![WhatsApp Image 2024-09-05 at 21 34 55_dfd95452](https://github.com/user-attachments/assets/cddb1aea-dc45-42e5-b7b8-fba003961309)

![WhatsApp Image 2024-09-05 at 21 34 16_7da1de01](https://github.com/user-attachments/assets/44ef5925-af2f-42e9-a0b7-5a48f8f6e821)



iv) Creating the new test cell view

• Go to CIW window, Execute File-New-Cell view  Setup the new file form  Library: Select the one you created.  Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test  View: Schematic  Type: Schematic press OK
• Follow the step 3(ii) d to make the required connections image

Analog simulation by SPECTRE.

• In test cell view window 
• Launch – ADE L(Analog Design Environment)  Execute Setup—Simulation/directory/Host A new window opens  Set the simulation window to spectre and click ok  Execute Analysis – Choose. A window opens.  Select the type and set the specifications and press OK  Execute Output s—to be plotted – Select on Schematic  Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse • Execute Simulation -- Net list and Run image

`TRANSIENT ANALYSIS AND OUTPUT`

![WhatsApp Image 2024-09-05 at 21 23 54_76eeaeb7](https://github.com/user-attachments/assets/162f6dff-0933-4d8a-9efb-fd1b881bfc1b)


`DC ANALYSIS AND OUTPUT`

![WhatsApp Image 2024-09-05 at 21 30 20_4b67cb3f](https://github.com/user-attachments/assets/a1eee438-5f2e-49d9-bd7f-eff463bc0317)



`RESULT:`

![WhatsApp Image 2024-09-05 at 21 35 24_5ed28a73](https://github.com/user-attachments/assets/ab64d9a3-aa0e-4ba1-aad3-086b61ec15ce)


-Successfully designed the CMOS inverter schematic using Cadence EDA tools.

-The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.

-The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.
