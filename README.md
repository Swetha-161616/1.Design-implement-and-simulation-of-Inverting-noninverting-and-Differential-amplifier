# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="1280" height="724" alt="image" src="https://github.com/user-attachments/assets/f8133f5f-2b0e-4a4e-a672-89f8b8f2a609" />


**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/520ec185-8686-4891-8a96-9e7c787918e3" />

  **MODEL GRAPH:**

<img width="1086" height="678" alt="image" src="https://github.com/user-attachments/assets/1a76d8db-e72b-4f1e-9edb-d5600303090d" />

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/bdb3f82b-c429-44f5-a9a8-9e9e8f355219" />


  **TABULATION:**
 
<img width="1280" height="443" alt="image" src="https://github.com/user-attachments/assets/803273cc-853b-4be8-8d28-0cee402578de" />

**MODEL CALCULATION:**
<img width="1178" height="446" alt="image" src="https://github.com/user-attachments/assets/053f176c-91fa-49fd-bd2f-b2723d963e1f" />

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1114" height="844" alt="image" src="https://github.com/user-attachments/assets/435195bf-6a69-4aa5-85ac-c9557e711d5d" />

  **MODEL GRAPH:**

<img width="1186" height="1040" alt="image" src="https://github.com/user-attachments/assets/2d91e84b-1cc8-4e6f-a5b2-cfa77a22f516" />

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/acb64276-0d8c-4361-9520-53fafdd01ed2" />


  **TABULATION:**
<img width="1280" height="187" alt="image" src="https://github.com/user-attachments/assets/f327d752-119b-44b5-8150-4c9153f98856" />
<img width="1280" height="326" alt="image" src="https://github.com/user-attachments/assets/55cd51e0-321d-4636-9039-7a2faf428c04" />


  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**

<img width="1224" height="892" alt="image" src="https://github.com/user-attachments/assets/b6545020-37d5-4f0a-9dba-39267e0ae473" />

  **MODEL GRAPH:**
<img width="1192" height="880" alt="image" src="https://github.com/user-attachments/assets/600c63ec-0c79-4c26-a1f2-97bbaa5f6f55" />

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/786e82bb-197d-4dba-bb9d-0ce8cbb5aaf5" />


  **TABULATION:**
  <img width="1280" height="563" alt="image" src="https://github.com/user-attachments/assets/d2cc8986-00e8-4f63-b488-e2c0e1767de5" />
  
   <img width="1280" height="668" alt="image" src="https://github.com/user-attachments/assets/c97c1f99-28e1-4df8-9455-eeb3efb86240" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  
  <img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/38d46e08-aa7e-432a-9ffe-1bb870365cb5" />

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






