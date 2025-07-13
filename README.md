# SSCS-Chipathon-2025---bitsamaMirai
## Track Digital Block 

## About Project 
In our project we are going to design 3-input XOR for GF180MCU 9 tracks and/or 12 tracks to expand the library. 
We chose XOR because we are familiar with its use as a parity bit generator. 

## XOR 3
### Drive Strength: 1X
### Track: 9 tracks
### VDD: 3.3 V

## Target Specs
Area: < 80 μm2
Input Capacitance: < 0.0075 pF
Delay: < 1.0 ns
Output Load: < 0.001 pF
Dynamic Energy: < 0.4 uW/MHz
Leakage Power: < 0.25 nW

## Referred to the existing cells’ specs below:
https://github.com/fossi-foundation/globalfoundries-pdk-libs-gf180mcu_fd_sc_mcu7t5v0/blob/main/cells/xor2/gf180mcu_fd_sc_mcu7t5v0__xor2_1.rst
https://github.com/fossi-foundation/globalfoundries-pdk-libs-gf180mcu_fd_sc_mcu7t5v0/blob/main/cells/xor3/gf180mcu_fd_sc_mcu7t5v0__xor3_1.rst
https://github.com/stineje/globalfoundries-pdk-libs-gf180mcu_osu_sc/blob/main/gf180mcu_osu_sc_gp9t3v3/cells/xor2/gf180mcu_osu_sc_gp9t3v3__xor2_1.lib


## Objectives 
1. Perform a schematic design using the pull-up and pull-down network methods.
functions obtained from the minterm of three XOR inputs.
2. Perform the schematic design using the Xschem application.
3. Perform a logic gate test bench using the Xschem application.
4. Perform layout with Magic.
5. Compare the Magic Layouting bench test results with the previous schematic.
6. Do the characterization

## Team Members 
1. Keertha N
2. Roy Victor Roberto
3. Reinhard Iven
4. Kana Takizawa

## Time line and Job 
### Week 1 : 14 - 18 July Schematic PDN and PUN Network and testbench by Reinhard Iven & Roy
method : using karnaugh map to find minterm function and then apply it to schematic for PUN and PDN functions
key of indicator success : A suitable testbench for 3-input XOR logic.

### Week 2 : 21 - 25 July Layouting using Magic by Kana Tazikawa and Keertha N 
method : design layout by constraint of GFMCU180 for the XOR 3 input by using Magic
key of indicator succes : A suitable testbench for 3-input XOR logic.

### Week 3 : 28 July - 2 August Implementation and Compare between Xschem and Magic Keertha N , Reinhard Iven , Roy
method : Compare the design Magic and schematic Xschem then finish the standard cell template 
key of indicator succes : verification and timing 

### Week 4 : 2 August - 20 August Characterization 
method : Layout, DRC, LVS, PEX  
key of indicator succes : still on going 

### Week 5 : 20 August - 5 September Integration and Verification 
method : still on going 
key of indicator succes : synthesis succesfully and measureable in timing and size of transistor 


