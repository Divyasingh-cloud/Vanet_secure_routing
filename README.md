# VANET Secure Routing Protocol Simulation

This project demonstrates a prototype implementation of a **secure routing protocol for Vehicular Ad Hoc Networks (VANETs)** using Python.  
It focuses on ensuring **message integrity** and detecting **tampering** in vehicle-to-vehicle communication using **cryptographic hash functions**.

## Author
**Divya Singh**  
Email: divyasingh.divz@gmail.com

---

## Problem Statement
Vehicular Ad Hoc Networks (VANETs) allow vehicles to wirelessly exchange messages to improve traffic safety and communication.  
However, VANETs are highly susceptible to security attacks such as data tampering, impersonation, and message modification.  
This project simulates a lightweight protocol using cryptographic hash functions to ensure secure and authentic message exchange.

---

## Features
- Simulates multiple vehicles with varying speed and movement
- Generates secure vehicle messages with:
  - SHA-256
  - SHA-1
  - MD5
  - BLAKE2b
  - SHA3-256
- Detects message tampering and invalid integrity
- Visualizes:
  - Hash computation times
  - Vehicle speed over time
  - Vehicle position tracking

---

## Technologies Used
- **Python 3**
- `hashlib` – cryptographic hashing
- `matplotlib` – plotting and visualization
- `pandas` – data tracking and analysis

---

## How to Run

1. Download or clone this repository:https ://GitHub.com/yourusername/Vaner_sercure_routing.git
2.  Install required libraries:pip install matplotlip pandas
3. Run the simulation:python main_simutation.py
4.  ---

## Output

- Logs showing valid and tampered message verification
- Hash function performance (boxplot)
- Vehicle movement plots (speed and position)

---

## Future Scope

This simulation is a prototype. Future enhancements can include:
- Full-scale implementation in **NS-3** or **OMNeT++ with SUMO**
- Simulation of attacks like **Sybil**, **Replay**, or **Blackhole**
- Lightweight digital signature integration

---

## License
This project is provided as part of an internship submission and is free for educational and academic use.
