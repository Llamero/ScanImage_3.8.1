# Backup of ScanImage Release 3.8.1
## Description
This is a full-featured open-source release of ScanImage.  This release works on galvo-galvo microscopes only.

## Requirements
### Hardware
NI DAQ PCI-6110 (Dev1)

NI DAQ PCIe-6321 (Dev2)

### Software
Matlab 2013b

NI-DAQmx version 9.8


## Wiring
![Wiring schematic](https://github.com/Llamero/ScanImage_3.8.1/blob/main/Images/BreakoutBoxWiringDiagram2.png)
<-> = Connection on the same Daq, <---> = Connection between Daqs

Dev1 P0.0 <-> user1 <-> PFI0

Dev1 Pfi1 <-> user2 <---> Dev2 user2 <-> ext trig

Dev1 PFI10 <---> Dev2 pfi9

Dev1 pfi14 <---> Dev2 pfi8

Dev2 p0.0 <-> user1
