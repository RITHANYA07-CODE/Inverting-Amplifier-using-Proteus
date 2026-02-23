# Inverting-Amplifier-using-Proteus

## Experiment 1
Design and Simulation of Inverting Amplifier using Op-Amp (μA741) in Proteus

## Aim
To design and simulate an Inverting Amplifier using μA741 Op-Amp in Proteus Design Suite and verify the voltage gain experimentally.

## Apparatus / Components Required

| S.No | Component | Specification | Quantity |
| :---: | :--- | :--- | :---: |
| 1 | Op-Amp IC | μA741 | 1 |
| 2 | Resistor $R_1$ | 10 kΩ | 1 |
| 3 | Resistor $R_f$ | 100 kΩ | 1 |
| 4 | Signal Generator | Sine wave, 1 kHz | 1 |
| 5 | Dual DC Power Supply | +15V, -15V | 1 |
| 6 | CRO / Oscilloscope | Virtual (Proteus) | 1 |
| 7 | Connecting Wires | — | As required |

## Theory
An Inverting Amplifier is a closed-loop amplifier configuration where the input signal is applied to the inverting terminal (-) of the op-amp through resistor R1, and feedback resistor Rf is connected between output and inverting terminal. The non-inverting terminal (+) is grounded.

## Circuit Description
•	Pin 2 → Inverting input  
•	Pin 3 → Non-inverting input (Grounded)  
•	Pin 6 → Output  
•	Pin 7 → +15V  
•	Pin 4 → -15V  
The input sine wave is applied through R1 and output is taken from pin 6.

## Circuit Diagram

<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/f23fdfb0-f082-4e34-89f3-9c106fd3dd09" />

## Tabulation
Input Voltage (Vin)	Theoretical Gain (Av)	Theoretical Vout	Practical Vout (Proteus)

## Observation Table

| Input Voltage ($V_{in}$) (Peak) | Theoretical Gain ($A_v$) | Theoretical Output ($V_{out}$) | Practical Output (Proteus) | 
| :---: | :---: | :---: | :---: | 
| 0.5 V | -10 | -5.0 V | -4.98 V | 
| 1.0 V | -10 | -10.0 V | -9.95 V | 
| 1.2 V | -10 | -12.0 V | -11.92 V | 
| 1.5 V | -10 | -15.0 V | -14.2 V (Saturated) |

## Simulation Procedure (Proteus)
1.	Open Proteus Design Suite
2.	Select components:  
•	μA741  
• Resistors  
•	AC Signal Generator  
•	Oscilloscope  
3.	Connect circuit as per inverting amplifier configuration.
4.	Set:  
•	R1 = 10kΩ  
•	Rf = 100kΩ  
•	Input = 1V, 1kHz sine wave  
5.	Apply ±15V power supply.
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
   
##  Waveform Observation
•	Input: Sine wave  
•	Output: Amplified sine wave  
•	Phase Shift: 180°  
•	Gain ≈ -10  

<img width="1367" height="866" alt="image" src="https://github.com/user-attachments/assets/b147b7c3-28c1-4cb9-9124-327426d66d53" />

## Result
The Inverting Amplifier using μA741 Op-Amp was successfully designed and simulated in Proteus.
The practical output voltage closely matches the theoretical value.
The gain obtained is approximately -10, and the output waveform is inverted with respect to the input waveform.
