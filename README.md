# 3.Design-implement-of-Schmitt-trigger-circuit-using-Op-amp
**Aim:**
To design and implement Schmitt-trigger-circuit-using-Op-amp

**APPARATUS REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	2
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,27K,39K,33K	1
7.	Connecting wires and probes	As required	

**THEORY:**

The circuit shows an inverting comparator with positive feedback. This circuit converts irregular shaped wave forms to a square wave or pulse. The circuit is known as the Schmitt trigger (or) squaring circuit. The input voltage Vin changes the state of the output Vo every time it exceeds certain voltage levels called the upper threshold voltage VUT and lower threshold voltage VLT.
When Vo= - Vsat, the voltage across R1 is referred to as lower threshold voltage, VLT. When Vo=+Vsat, the voltage across R1 is referred to as upper threshold voltage VUT. The comparator with positive feedback is said to exhibit hysteresis, a dead band condition.
 

**DESIGN:**
1.	Select the desire value of Vut & Vlt with same magnitude & opposite polarity. Let VUT = 0.3V & VLT = -0.3V.
2.	For Op-amp 741C ± Vsat ≡ ±12V. And assume Vref = 0, Since the another end of R1 is grounded.
3.	If Vo = +Vsat the voltage at the positive terminal will be (voltage from potential divider R1 & R2).
VUTP = [R1/(R1+R2 )](+Vsat)
VLTP = [R1/(R1+R2 )](-Vsat) 0.3=[R1/(R1+R2 )](+12)
0.3/12=[R1/(R1+R2 )]
0.025(R1+R2)=R1
0.025R2=(1-0.025)R1 R2=(0.975/0.025)R1 R2 = 39 R1
Assume R1=1KΩ
R2=39 KΩ

 
**PROCEDURE:**
1.	Design the value of circuit components and select VUT & VLT as given in the design procedure.
2.	Connect the circuit as shown in the circuit diagram.
3.	Apply the input signal to the input terminal of op-amp & set VUT & VLT values.
4.	Note down the readings from the output waveform.
5.	Plot the graph & show the relationship between Input sine wave & Output


  **CIRCUIT DIAGRAM** 
  
<img width="864" height="696" alt="WhatsApp Image 2026-09-14 at 8 15 01 PM" src="https://github.com/user-attachments/assets/4c4a0ffe-028a-486d-b78b-fea38dbff82b" />


  **MODEL GRAPH:**
<img width="934" height="505" alt="WhatsApp Image 2026-09-14 at 8 15 29 PM" src="https://github.com/user-attachments/assets/0c0e605b-bd6e-4a21-a5ec-4567fd2da0fb" />


  **TABULATION:**
 <img width="975" height="430" alt="WhatsApp Image 2026-09-14 at 8 15 14 PM" src="https://github.com/user-attachments/assets/d41f8e6d-47d5-4102-b6d4-baff8eb1ef70" />


**GRAPH:**

<img width="948" height="1280" alt="WhatsApp Image 2026-09-14 at 8 18 32 PM" src="https://github.com/user-attachments/assets/210fb815-df53-43ad-a81d-9cb66006d84e" />




**RESULT:**
Thus a Schmitt trigger is designed and tested using op-amp IC 741.
 

