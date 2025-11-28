
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---![WhatsApp Image 2025-11-28 at 10 15 22_f948b075](https://github.com/user-attachments/assets/60f46f86-3666-49a5-9e2a-d435092f4a22)


## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---


## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. <img width="476" height="192" alt="517934085-523ed762-09f9-42e7-831b-3476afe4a961" src="https://github.com/user-attachments/assets/12a6d666-3ce7-44d2-a70a-a7d445f0e9fc" />
<img width="459" height="189" alt="517934110-58d57898-d00e-4547-9cec-0129daf5c6f0" src="https://github.com/user-attachments/assets/d4812898-5881-404b-9fd3-52ed683472a6" />


5. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
6. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
7. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
   
8. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
9. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM


---<img width="1280" height="976" alt="514708144-dee9a68f-27eb-4a66-8b11-13b14c7e3b36" src="https://github.com/user-attachments/assets/99e8acb7-6068-44a3-92b1-2573c16ffdc6" />


## 📊 TABULATION

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
|                        |                         |
|                        |                         |
|                        |                         |

---

## 📈 MODEL GRAPH
*(Insert graph of Vf vs If here)*
![WhatsApp Image 2025-11-28 at 10 15 22_8c2f5f98](https://github.com/user-attachments/assets/8f17aed3-cb29-4249-894a-d366d27e8f63)

---
[Uploading EXP.pdf…]()

[Uploading EXP 2F.pdf…]()

## ✅ RESULT
![WhatsApp Image 2025-11-28 at 10 15 23_0dd4b710](https://github.com/user-attachments/assets/66d521fe-b6ce-4529-b8ce-91a71a34056a)

- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
