# EXP-5-CHARACTERISTICS-OF-SCR
1. AIM
To study and plot the V-I characteristics of a Silicon Controlled Rectifier (SCR), and to determine its forward breakover voltage and holding current.
SOFTWARE REQUIRED:
LT-Spice
3. APPARATUS REQUIRED
S. No.	Component	Specification	Quantity
1	SCR	2P4M	1
2	Resistor	1 kΩ	2
3	Regulated Power Supply	Dual (0–30 V)	1
4	Voltmeter	0–30 V	2
5	Ammeter	0–30 mA	2
6	Breadboard	—	1
7	Connecting wires	—	As required
4. THEORY
An SCR is a four-layer PNPN semiconductor device having three terminals: anode, cathode and gate. In the normal OFF state, the device restricts current. When the anode-to-cathode voltage exceeds a certain threshold (forward breakover voltage) or a suitable gate current is applied, the SCR turns ON and conducts current.
Once the SCR is turned ON, it remains in the ON state even after the gate current is removed, provided the anode current remains above the holding current. When the anode current falls below the holding current for an appropriate period, the SCR switches OFF. A positive gate current can therefore be used to trigger the device into conduction.
The SCR V-I characteristic consists of forward blocking, forward conduction and reverse blocking regions. In the forward blocking region, only a small leakage current flows. After triggering, the SCR enters the forward conduction region, where the current increases substantially while the voltage across the device is low. In reverse bias, only a small reverse leakage current flows until breakdown.
5. PIN DIAGRAM / SYMBOL

6.SCR terminals:  Anode (A)   |   Gate (G)   |   Cathode (K)

<img width="1367" height="780" alt="Screenshot 2026-11-17 213208" src="https://github.com/user-attachments/assets/8f2685a1-4fc3-4ccf-b623-8a9985e9ac7d" />


7. CIRCUIT CONNECTION DIAGRAM:
8. 
<img width="1917" height="1022" alt="Screenshot 2026-11-17 202322" src="https://github.com/user-attachments/assets/ccfb1726-0309-4d09-894c-0124db4079b1" />

9. 
The main anode-cathode circuit consists of the regulated DC supply, a 1 kΩ series resistor, an ammeter and the SCR. A voltmeter is connected across the SCR to measure VAK. A separate regulated supply is connected through a 1 kΩ resistor to the gate, with a gate ammeter to measure IG.
 
Reference circuit diagram from the supplied lab record.

6. OUTPUT GRAPH:

<img width="1912" height="1007" alt="Screenshot 2026-11-17 202501" src="https://github.com/user-attachments/assets/8199ab82-3a0c-4753-8898-24f4439e27ba" />

Plot VAK (V) on the X-axis and IAK (mA) on the Y-axis. The curve indicates the forward blocking region, forward breakover point, forward conduction region, holding current and reverse blocking region.
 
Reference characteristic curve from the supplied lab record.
7. PROCEDURE
1. Make the connections as shown in the circuit diagram.
2. Set R1 and R2 to the mid-position and set the regulated supplies V1 and V2 to minimum.
3. Set the gate current IG to approximately 0.7 mA. Check that the forward breakover voltage is within the available supply range.
4. Slowly vary the anode supply VAK in suitable steps and note VAK and IAK at each step until the SCR conducts. Note the maximum VAK just before the SCR conducts; this is the forward breakover voltage.
5. Finding latching current: Ensure that the SCR is in the conducting state. Start reducing the anode voltage in steps while simultaneously switching OFF the gate supply. The corresponding anode current at the point at which the SCR ceases to remain latched is the latching current IL.
6. Finding holding current: Ensure that the SCR is conducting and switch OFF the gate supply permanently. Slowly reduce VAK and note IAK at each step. The anode current just before it drops to zero is the holding current IH.
7. Reverse the anode supply polarity and vary the reverse voltage in steps. Note the corresponding reverse current values.
8. Plot the forward and reverse characteristics using the tabulated values and determine the SCR forward resistance from the graph.
9. Repeat the procedure for another suitable gate current (for example, IG = 1.2 mA) and verify the characteristics.
10. 
 RESULT:

Thus the phase control characteristics of SCR using LT-spice is stimulated and verified 

