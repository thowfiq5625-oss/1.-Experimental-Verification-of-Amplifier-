#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![WhatsApp Image 2025-11-30 at 21 18 34_9f1b0f54](https://github.com/user-attachments/assets/01219ad3-9d79-45e9-ba26-fc8e7fb66d14)


MODEL GRAPH 

<img width="543" height="357" alt="image" src="https://github.com/user-attachments/assets/1836d120-768e-454f-bfe4-682ce70ea7a1" />



DESIGN:
![WhatsApp Image 2025-12-04 at 10 58 21_7ec026f3](https://github.com/user-attachments/assets/d2fc0437-5ea7-4229-b7c4-dbe9253b7686)


PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![WhatsApp Image 2025-11-30 at 21 19 22_a99bf7e0](https://github.com/user-attachments/assets/e372b8b0-63be-4cde-b114-37de5565be75)



---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-30 at 21 19 23_f645dabe](https://github.com/user-attachments/assets/5966d0da-9a54-4ba7-a70f-5df3316bfd3f)

---

### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM


![WhatsApp Image 2025-11-30 at 21 22 16_96db68e7](https://github.com/user-attachments/assets/7f833c2a-230c-4286-a7eb-d2b32ae992d1)

---

## MODEL GRAPH

<img width="456" height="340" alt="image" src="https://github.com/user-attachments/assets/00c7aaec-b4d8-414e-afa3-e985eb3dd902" />

---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

![WhatsApp Image 2025-11-30 at 21 22 16_f0affc01](https://github.com/user-attachments/assets/885fa4d8-7583-4eab-b775-57981e56781c)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-30 at 21 22 19_9b2454b1](https://github.com/user-attachments/assets/995c9512-c495-4b79-945a-db3948febb45)


---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-30 at 21 25 02_b25d0531](https://github.com/user-attachments/assets/557c8cbb-2a5d-40ed-ab05-4b57e1963947)

## MODEL GRAPH
<img width="678" height="334" alt="image" src="https://github.com/user-attachments/assets/6aa1b9dd-b112-4be1-a37a-d5ee19607b1d" />

---

## DESIGN

![WhatsApp Image 2025-12-04 at 10 58 21_7ec026f3](https://github.com/user-attachments/assets/701811b4-8e23-4f71-b82d-aae5dac88d3d)


---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![WhatsApp Image 2025-11-30 at 21 25 04_11f02ee7](https://github.com/user-attachments/assets/dfadce5d-ebfd-4e7e-bcff-23c8611fa0eb)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-30 at 21 25 22_65880943](https://github.com/user-attachments/assets/1e48972f-981e-4b89-bc55-32c1a02459a5)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![WhatsApp Image 2025-11-30 at 21 25 24_5aaf31b4](https://github.com/user-attachments/assets/ba2a6ab7-0e34-4b70-b5e6-999064851711)

PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

![WhatsApp Image 2025-11-30 at 21 25 25_a3a02791](https://github.com/user-attachments/assets/350c9557-3f1b-400b-8e3f-e70e587103ac)


---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-30 at 21 25 26_70f34485](https://github.com/user-attachments/assets/f5299fa5-04d8-4ec9-a01c-ec703e311e1f)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
