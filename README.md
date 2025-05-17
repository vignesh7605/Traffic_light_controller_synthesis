# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

### Synthesis RTL Schematic :
![WhatsApp Image 2025-05-17 at 14 19 59_6e319e00](https://github.com/user-attachments/assets/e1a8f091-f861-4042-bee6-70635ce58c8c)

### Area report:
![WhatsApp Image 2025-05-17 at 14 20 01_f85911f7](https://github.com/user-attachments/assets/70a78c0b-9fec-4018-aabf-87166774857f)


### Power Report:
![WhatsApp Image 2025-05-17 at 14 20 00_b3addeb9](https://github.com/user-attachments/assets/af6dd12c-38cc-4197-b1d5-48edd52c4379)

### Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
