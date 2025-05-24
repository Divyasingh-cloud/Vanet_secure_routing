# VANET Secure Routing Protocol Simulation

This project demonstrates a prototype implementation of a **secure routing protocol for Vehicular Ad Hoc Networks (VANETs)** using Python. 
It focuses on ensuring **message integrity** and detecting **tampering** in vehicle-to-vehicle communication using **cryptographic hash functions**.

## Author
**Divya Singh**  
Email: divyasingh.divz@gmail.com

---

## Problem Statement
VANETs allow vehicles to communicate with each other and infrastructure, but they are vulnerable to attacks such as message tampering and impersonation. 
This simulation demonstrates a lightweight solution using hash-based message authentication.

---

## Features
- Simulates multiple moving vehicles with random speeds
- Secure message generation using SHA-256, MD5, SHA-1, BLAKE2b, and SHA3-256
- Detection of message tampering through hash validation
- Visual output using plots: hash timings, speed, and position tracking

---

## Technologies Used
- Python 3
- `hashlib` for cryptography
- `matplotlib` for plotting
- `pandas` for data processing

---

## How to Run
1. Clone this repository or download the files.
2. Install the required Python libraries:
   ```bash
   pip install matplotlib pandas
   ```
3. Run the simulation:
   ```bash
   python main_simulation.py
   ```

---

## Output
- Valid and tampered message detection logs
- Boxplot showing performance of different hash algorithms
- Speed and position tracking of vehicles

---

## Future Scope
This prototype can be extended in simulators like **NS-3** or **OMNeT++ with SUMO** to simulate realistic VANET scenarios and evaluate resistance to advanced attacks such as Sybil, Blackhole, and replay attacks.
