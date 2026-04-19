# FPGA Music Generator
For Alchitry Au FPGA using Lucid V2  
by Group 34 (Alvin, Nicholas, Reeve, Ganesh, Le Bin, Michael, Edward)

This project was created as an audio component for the 1D Project of SUTD's 50.002 Computation Structures 2026

## Components
**Tone generator**: Creates 50% duty cycle square wave  
**Note period ROM**: Get number of clock cycles per period of each note  
**Music ROM**: Sheet music translated to (Note frequency, Note duration) format  
**BPM ROM**: Defines number of clock cycles for each different count duration  
**Melody**: Instances each of the necessary files to play music  

## Included Music
Tetris (Korobeiniki)  
Never gonna give you up (chorus only)

## Necessary formulas
**Note period**: Period = Clock Speed / Frequency  
**BPM conversion**: Count = Clock Speed / (BPM/60)
