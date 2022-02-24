# IITH-SNPS-Analog-Hackathon

The following project was done on by custom compiler tool offered by synopsis via their cloud platform (centos operating system) , and the simulation was run using Primewave .
This project was held under a 3 week analog hackathon held by IITH , Synopsis and Meity . The circuit and the simulation details are self explanatory . The initial survey report has also been added to the repository . The purpose of the project for me was to introduce myself to industry level VLSI softwares , and gain a basic understanding of MOSFET's

# About :
* Name - Ayush Agarwal 
* College - IIT BHU Varanasi 
* Branch - Electronics 
* Year - 2nd year B.Tech 
* Project - NAND gate using MOSFET's (Metal Oxide Semiconductor Field Effect Transistors)  

# Introduction :

Complementary Metal-Oxide Semiconductors (CMOS) logic devices are the most common devices used today in the high density, large number transistor count circuits found in  everything from complex microprocessor integrated circuits to signal processing and communication circuits. The CMOS structure is popular because of its inherent lower power 
requirements, high operating clock speed, and ease of implementation at the transistor level. This project consists of constructing simple NAND gate out of both p and n channel Metal Oxide Semiconductor Field Effect Transistors (MOSFET) . NAND gate is known as " Universal Gate " since all the other logic gates can be expressed in terms of NAND gate , and hence is widely used in the VLSI industry to make circuits .

# Circuit Diagram :

![image](https://user-images.githubusercontent.com/86561124/155496663-ed3c52b3-0511-4835-a781-80476b77a45b.png)

# Truth table for NAND gate :

![image](https://user-images.githubusercontent.com/86561124/155496794-57a650f0-16d8-47b3-82ab-60e250410360.png)


# Tools used :

* Synopsys Custom Compiler:

 The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

* Synopsys Primewave:

PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

* Synopsys 28nm PDK:
 
 The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

# Schematic :
![image](https://user-images.githubusercontent.com/86561124/155483381-5babb07c-6d9a-4f23-a536-64b44e89a549.png)
![image](https://user-images.githubusercontent.com/86561124/155483271-24716346-65a7-42b9-80a1-b6b240d37ea1.png)

# Testbench :
![image](https://user-images.githubusercontent.com/86561124/155483778-341e2e9f-3371-484b-bff5-b0f20327ea78.png)


# Waveforms for A , B and Y :

A : 0 0 1 1 0 

B : 0 1 0 1 0 

Y : 1 1 1 0 1 

![image](https://user-images.githubusercontent.com/86561124/155483636-71d09e6f-d9c9-4168-9db9-39d83d9ad7dc.png)

# References:

( References read by me during Literature Survey ) 
* https://www.academia.edu/12642558/Semi_custom_Layout_Design_and_Simulation_of_CMOS_NAND_Gate
* http://cmosedu.com/jbaker/courses/ee421L/f13/students/wolvert9/Lab%206/Lab6.html
* http://ece-research.unm.edu/jimp/vlsi/misc/cmostran.htm
* https://www.youtube.com/watch?v=YAQbPbI-2XI

# Acknowledgements 

* https://hackathoniith.in/
* https://www.synopsys.com/
* https://www.vlsisystemdesign.com/
* https://github.com/kunalg123 , Founder, VSD Corp. Pvt. Ltd
* https://iith.ac.in/

