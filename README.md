#  Digital Lock Logic – Proteus Simulation

**A digital lock system with timer logic built in Proteus ISIS**

This project simulates a secure digital lock using discrete logic components. 
The circuit validates a user‑entered code 3 of them with a safety stop button (although realistcially just cut the 5 volt wire)
and, if correct, enables a timed access window. It demonstrates key fundamental concepts in digital electronics: 
combinational logic, sequential logic (flip‑flops), counters, and display drivers.

The design was originally conceived with internal project name "bomb" like in the movies with 3 incrementing ins 
but my other peers does not like the name due to the association with terrorism
To focus on the core digital lock functionality, the repository has been renamed to **Digitallock_logic**.

---

## 📌 Features

- **3‑digit code entry** using buttons to increment when its over 9 it will go back to 0
- **Code comparator** built from logic gates (AND/OR/XOR)
- **State control** with flip‑flops utilizing  JK or D flipflop to manage locked/unlocked states and confimed shutdown
- **Timer circuit** using a 555 timer or a counter (e.g., 74LS192) to generate a fixed access period starting in 60 seconds
- **Visual indicators**: LEDs for “Locked” / “Unlocked”, and a 7‑segment display for timer countdown
- **Reset & error handling**: Wrong code resets the entry without unlocking

---

## 🛠️ Components & Tools

| Component          | Details                                    |
|--------------------|--------------------------------------------|
| Simulation Tool    | Proteus ISIS (8.x or later)                |
| Logic ICs          | 74LS series (gates, flip‑flops, counters)  |
| Input              | 3 buttons and                              |
| Display            | 7‑segment common cathode                   |
| Timer              | 555 timer in monostable mode or binary counter |
| Power              | 5V DC supply                               |

---

## 📂 Repository Contents


## 🚀 Running the Simulation

1. Download and install **Proteus ISIS** (version 8 or later).
2. Open the file `Digital_Lock.pdsprj`.
3. Press the **Play** button to start the simulation.
4. Enter the correct code (default: e.g., 1‑2‑3‑4) using the "unrevealed"
5. Observe the “Unlocked” LED and the timer countdown on the 7‑segment display.

