# 3-STAGE-OSCILLATOR-
## REG NUM :25011767
## NAME :Khotla Gagan Prathyush

## Aim: To Design CMOS 3 stage oscillator and OP analysis.

## Tools Used: Virtuoso Schematic Editor is used for the design and analysis.

## Theory:
3-stage oscillator consists of three amplifier stages connected in a feedback loop, each providing a phase shift of 60°, resulting in a total 180° phase shift. Combined with the 180° phase shift from inversion, the loop gain and phase conditions for oscillation are satisfied. Commonly built using RC networks, it generates stable sine waves and is widely used in low-frequency applications.

## Procedure:
•	Click new -> library attach to an existing technology library gpdk045(in
technology file )
•	new cell view (name of the layout)

## For schematic:
•	Pick the components NMOS, PMOS, ground, VDD and voltage source.
•	Connect the wire as per the schematic diagram.

<img width="554" height="412" alt="3-stage oscillator symbol diagram" src="https://github.com/user-attachments/assets/249cba17-63cb-4e0e-9ab2-585b5bc71646" />

fig-symbol diagram in cadence 

<img width="895" height="439" alt="image" src="https://github.com/user-attachments/assets/ba32edfc-068a-4f94-8513-9adf76e087be" />

Transient Analysis and OP:
•	In the Analysis section, select transient.
•	In the stop time type 1u and click OK.
•	In the transient Analysis section, turn on Save transient Operating Point. 
•	Check the enable button and then click Apply.
•	Click OK in the Choosing Analyses Form.
•	Click OK in the Choosing Analyses Form.
Execute Outputs: 
To be plotted – Select on Schematic in the simulation window. 
Follow the prompt at the bottom of the schematic window, Click on output net Vout, input 
net Vin of the Inverter. 
Execute Simulation:
Net list and Run in the simulation window to start the Simulation. 
When simulation finishes, the transient automatically will be popped up along file.

## waveform:
<img width="975" height="565" alt="image" src="https://github.com/user-attachments/assets/5ed69e80-447c-4bac-8d58-d9a1f3d402f1" />


## Result:
Design of CMOS 3 stage oscillator and transient performed and output waveforms are obtained.
