# Mixed Signal Circuit Design and Simulation Marathon

# IMPLEMENTATION-OF-RVMYTH MIXED SIGNAL

      Abstract
      Reference Circuit Diagram
      Circuit Details
      Methodology Proposed
      EDA Tools Used
      Makerchip
      Creating model of rvmyth(RISC-V) using Ngveri
      Schematics
      Output waveforms
      GAW Waveforms
      Acknowlegemnts
      References
      
 # ABSTRACT
 
 RISC-V is an open standard instruction set architecture (ISA) and is based on established reduced instruction set computer (RISC) principles. This paper describes the circuit implementation & simulation of flash type ADC. In this development of processor based on the open- source RVMYTH mixed signal circuit is presented. This processor is designed for targeting low-cost embedded devices. A RISC-V development and validation framework with assembling tools. The resulting processor is a single core, in-order, RISC-V processor with low hardware complexity. The proposed processor is implemented in Verilog. RISC-V is a free and open ISA enabling a new era of processor innovation through open standard collaboration.
 
 # REFERENCE CIRCUIT DIAGRAM
 
 
 
 # CIRCUIT DETAILS

 As shown in the figure we have analog circuit and digital circuit in which altogether formed a mixed circuit signal in the RVMYTH mixed signal circuit.
The analog part consists of a clockwise generator connected to resistor capacitor and finally all this grounded. Digital circuit consists of digital board. In between analog and digital circuit ADC and DAC bridges are used as a connector between analog and digital circuit which together forms a mixed signal circuit. 
The purpose of this project is to integrate rvmyth (RISC-V) with digital to analog converter (DAC) and perform simulation using end-to- end open-source EDA tool
