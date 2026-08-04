# Ex-4-BOM-for-Circuit-board

**Aim  **
To create and generate the Bill of Materials (BOM) for a printed circuit board (PCB) design using Proteus Design Suite, and to understand the importance of component documentation in PCB manufacturing and assembly.

**Apparatus Required**

S.No	Components/Software	Specification

1	Computer System	Windows 10/11
2	Proteus Design Suite	Version 8.0 or above
3	Electronic Circuit Schematic	Any completed circuit
4	PCB Layout	Designed in Proteus ARES
5	Electronic Components	Resistors, Capacitors, ICs, Diodes, LEDs, Connectors, etc.
6	Printer (Optional)	For BOM report
7	Microsoft Excel/PDF Reader	To view exported BOM

**Theory**

A Bill of Materials (BOM) is a comprehensive list of all the electronic components required to manufacture and assemble a printed circuit board (PCB). It acts as a blueprint for production by providing complete information about every component used in the circuit.

In PCB design, the BOM is automatically generated from the schematic after assigning component values and PCB footprints. It contains detailed information such as:

Reference Designator

Component Name

Component Value

Package/Footprint

Quantity

Manufacturer Part Number (optional)

**Description**

The BOM is one of the most important documents used during PCB fabrication because it enables engineers, purchasing departments, and manufacturers to procure the correct components and assemble the circuit accurately.

Proteus Design Suite provides an automated Bill of Materials Generator, which extracts component information directly from the schematic database. This minimizes documentation errors, saves time, and ensures consistency between the schematic and PCB layout.

The generated BOM can be exported in various formats such as:

Microsoft Excel (.xls/.xlsx)

CSV

Text File

HTML

PDF (after conversion)

A typical BOM entry includes:

Reference	Component	Value	Package	Quantity
R1	Resistor	1 kΩ	AXIAL-0.4	1
C1	Capacitor	1000 µF	RADIAL	1
D1–D4	Diode	1N4007	DO-41	4
IC1	Voltage Regulator	7805	TO-220	1
LED1	LED	Red	5 mm	1

An accurate BOM helps in:

Component procurement

Cost estimation

PCB assembly

Inventory management

Maintenance and troubleshooting

Manufacturing documentation

Thus, generating a BOM is an essential step before PCB fabrication and production.



**Procedure**

Open Proteus Design Suite.

Create or open an existing schematic project.

Ensure all components have:

Correct values

Reference designators

PCB footprints/packages

Verify that the schematic has no electrical errors.

Complete the PCB layout in the ARES module (if applicable).

Navigate to the Output or Reports menu.

Select Bill of Materials (BOM) generation.

Review the generated component list.

Verify the quantity, package, and component values.

Export the BOM as Excel, CSV, or Text format.

Save the generated report for PCB manufacturing and documentation.

**Output**

Generated Bill of Materials
Reference Designator	Component	Value	Package	Quantity
R1, R2	Resistor	1 kΩ	AXIAL-0.4	2
C1	Capacitor	1000 µF	RADIAL	1
C2	Capacitor	0.1 µF	Ceramic	1
D1–D4	Diode	1N4007	DO-41	4
IC1	Voltage Regulator	7805	TO-220	1
LED1	LED	Red	5 mm	1
J1	Connector	2-Pin	Terminal Block	1

**Observation**

All components are listed with correct reference numbers.

Component values and PCB footprints are verified.

Quantity of each component is automatically calculated.

BOM report is successfully exported for manufacturing.
<img width="1296" height="772" alt="image" src="https://github.com/user-attachments/assets/36c92356-6738-40e5-9181-32207ec71386" />
<img width="1296" height="218" alt="image" src="https://github.com/user-attachments/assets/30e8aebd-705c-41d2-a792-f51dc2bbc1df" />



**Result**

The Bill of Materials (BOM) for the circuit board was successfully generated using Proteus Design Suite. The BOM accurately listed all electronic components, their reference designators, values, quantities, and PCB footprints. The generated report can be used for component procurement, PCB assembly, manufacturing documentation, and quality control, ensuring efficient and error-free circuit board production.
