## LTspice tutorial - Modeling vacuum tube triodes
https://youtu.be/7v9dG1uteAQ?si=SxcTgqS8P0J22AEq
## 12AU7 Preamplifier with buffer LTSPICE Simulation
<img width="1147" height="296" alt="image" src="https://github.com/user-attachments/assets/82ac7647-3f08-445e-a5a4-01c2c4a0745b" />
<img width="1152" height="939" alt="image" src="https://github.com/user-attachments/assets/3905148d-c47c-4fb3-9cc6-1fdb897f5ac3" />

## Real 12AU7 Pre amplifier
<img width="771" height="478" alt="image" src="https://github.com/user-attachments/assets/3eadfcba-2280-490b-82da-3549af152c7c" />
<img width="720" height="960" alt="image" src="https://github.com/user-attachments/assets/1d525d41-f50f-4ea8-8b54-49c4071c551e" />

## Tubes Model Parameter:

```
12AX7 Subcircuit:
Cak=0.33p: Anode-to-cathode capacitance
Cga=1.6p: Grid-to-anode capacitance
Cgk=1.65p: Grid-to-cathode capacitance
Kg1=1060: Perveance scaling factor
ex=1.4: Exponent for the plate current equation
mu=100: Amplification factor
kp=600: Knee sharpness parameter
kvb=300: Grid voltage smoothing parameter
vgc=0: Grid-cathode voltage offset
Rgk=2k: Grid-cathode resistance

12AU7 Subcircuit:
Cak=0.24p: Anode-to-cathode capacitance
Cga=1.4p: Grid-to-anode capacitance
Cgk=1.6p: Grid-to-cathode capacitance
Kg1=920: Perveance scaling factor
ex=1.3: Exponent for the plate current equation
mu=17: Amplification factor
kp=330: Knee sharpness parameter
kvb=300: Grid voltage smoothing parameter
vgc=0: Grid-cathode voltage offset
Rgk=2k: Grid-cathode resistance

Usage Notes:
Pin Order: Both new models use 1=Anode, 2=Grid, 3=Cathode (same as the existing 6S19P).
Compatibility: The models retain the original VTT subcircuit structure, ensuring consistency.
Parameter Sources: Values are derived from Norman Koren's industry-standard vacuum tube models.
This update allows seamless simulation of 12AX7 and 12AU7 tubes alongside the original 6S19P model in SPICE-based circuit simulators.
```
## 12AX7 SRPP Preamplifier LTSPICE Simulation
<img width="1150" height="831" alt="image" src="https://github.com/user-attachments/assets/d4287139-7fd5-4703-afe3-2803f4a52977" />
<img width="1079" height="673" alt="image" src="https://github.com/user-attachments/assets/e1f7d191-e359-4846-a59a-2c971d525f15" />
<img width="1337" height="1112" alt="image" src="https://github.com/user-attachments/assets/c1e5c26e-b34e-40e6-85b3-a6b87585dd34" />
<img width="1304" height="879" alt="image" src="https://github.com/user-attachments/assets/964639c3-77e0-45d1-bfe5-a66196e8ef0e" />
<img width="2305" height="1757" alt="image" src="https://github.com/user-attachments/assets/21b1ad86-3923-4a0e-b19a-9e5c1a6ef50a" />




