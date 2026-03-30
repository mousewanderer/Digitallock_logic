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
4. Enter the correct code (default: e.g., idk) using the "unrevealed"
5. Observe the “Unlocked” LED and the timer countdown on the 7‑segment display.

What I would look like

# Structure
<img width="1321" height="773" alt="Screenshot 2026-03-30 205423" src="https://github.com/user-attachments/assets/f9ee6851-234d-405c-bf89-3e173136662a" />

<img width="621" height="370" alt="Screenshot 2026-03-30 205403" src="https://github.com/user-attachments/assets/4f281885-c73e-400a-8b46-8741a3fce36b" />

<img width="872" height="414" alt="Screenshot 2026-03-30 205352" src="https://github.com/user-attachments/assets/3c40b91b-3ce8-467f-8101-37eb08b4b93e" />

# Function
<img width="975" height="610" alt="Screenshot 2026-03-30 205342" src="https://github.com/user-attachments/assets/5fd29325-06fe-47c0-831e-5e161708c428" />
<img width="593" height="752" alt="Screenshot 2026-03-30 205333" src="https://github.com/user-attachments/assets/29e844c6-6194-4773-beba-7b2d1cf2b7b2" />

<img width="995" height="824" alt="Screenshot 2026-03-30 205319" src="https://github.com/user-attachments/assets/a2408721-0580-44db-b077-6222ccc49de4" />
<img width="1278" height="705" alt="Screenshot 2026-03-30 205247" src="https://github.com/user-attachments/assets/b435e15a-aa67-4df7-b959-ffb318c63480" />
<img width="1244" height="584" alt="Screenshot 2026-03-30 205435" src="https://github.com/user-attachments/assets/cf436406-70a8-476e-b5dc-e6558431fd5c" />

