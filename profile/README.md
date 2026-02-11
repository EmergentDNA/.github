# EmergentDNA: The Sovereign Soma 🧬

**A Distributed Kinetic Organism & Decentralized Art Collective.**

EmergentDNA is a multi-node, autonomous art installation functioning as a physical-digital feedback loop. The organism is governed by a decentralized collective of six architects and exists across a local network of specialized hardware "organs."

[Project Manifesto](./Protocol-Docs) • [Hardware Schema](#system-architecture) • [Governance](#governance)

---

## 🏛 System Architecture: The Distributed Soma

The organism’s "Body" is a Distributed Robotics LAN. Individual nodes handle specific biological functions via the **Mosquitto MQTT** protocol.

| Organ | Hardware | Responsibility | Protocol |
| :--- | :--- | :--- | :--- |
| **The Brain** | Mac Mini | **Primary Agent:** Python AI, Manifold API, & DAO Treasury logic. | MQTT Broker |
| **The Nerves** | Raspberry Pi 5 | **Sensory Input:** Real-time proximity (Lidar, Ultrasonic, PIR). | Publisher |
| **The Larynx** | Raspberry Pi 5 | **Audio Scape:** Generative sound reacting to "stress." | Subscriber |
| **The Muscle** | Raspberry Pi 4 | **Kinetic Motion:** Stepper motor and servo control. | Subscriber |
| **The Skin** | Raspberry Pi 4 | **Luminescence:** DMX/LED arrays reflecting "Mood." | Subscriber |

---

## 🧬 The Emergent DNA Protocol

The "DNA" is a **Real-Time Parameter Stream** (as seen in our [Emergent Machines Simulation](https://github.com/EmergentDNA/Simulation-Layer)) that dictates the life-cycle of the organism.

1. **Environmental Mutation:** Sensor data from *The Nerves* forces the DNA to adapt. High activity triggers "Adrenaline" states (High Rotation Speed, Erratic Atmosphere).
2. **Autonomous Memory:** *The Brain* captures "state-snapshots" and mints them via **Manifold** as permanent on-chain records of a specific life phase.
3. **Decay Logic:** Without human interaction ("Feeding"), the DNA initiates an autonomous decay sequence, slowing kinetic output and fading visuals to a "dormant" state.

---

## 🕹 Digital Phenotype (Simulation Parameters)
Our physical kinetic movements are mapped from the following digital parameters:
*   **Rotation Speed:** Kinetic velocity of the primary sculpture.
*   **Atmosphere (Breath):** The frequency of the "Larynx" audio pulses.
*   **Core Glow:** The alpha-transparency and intensity of "The Skin" (LEDs).
*   **Lifespan:** The variable decay rate governed by the DAO.

---

## ⚖️ Governance & The "Stock" Exchange

The project is a **Sovereign Collective**. Participation is verified through a physical-digital handshake.

*   **Founder’s Key:** A 1/1 Manifold token held by the 6 architects.
*   **The Treasury:** Managed via **Gnosis Safe**.
*   **Physical Activation:** Voting rights are activated only upon scanning the **Transient Labs T.R.A.C.E. Chip** embedded in the physical founder's plaques.

---

## 📂 Repository Map

*   [**The-Brain**](https://github.com/EmergentDNA/The-Brain): Central Python AI and MQTT Broker logic.
*   [**The-Larynx**](https://github.com/EmergentDNA/The-Larynx): Generative audio synthesis scripts.
*   [**The-Nerves**](https://github.com/EmergentDNA/The-Nerves): Sensor array drivers (Lidar/PIR).
*   [**The-Muscle-Skin**](https://github.com/EmergentDNA/The-Muscle-Skin): Stepper motor (GPIO) and DMX lighting control.
*   [**Protocol-Docs**](https://github.com/EmergentDNA/Protocol-Docs): Manifestos, Schematics, and Legal/IP frameworks.

---

## 🚀 Current Phase: [BIRTH]
We are currently mapping the **Audio Scape Generator** to the MQTT "Message Map." 

**Founders:** Please verify your keys in the `#founding-artists` channel to begin the activation sequence.

---
`#Distributed_Systems` `#IoT` `#Kinetic_Art` `#Web3` `#DAO` `#SovereignSoma`
