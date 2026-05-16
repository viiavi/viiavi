# Hi, I'm Vainavi (viiavi)
### Embedded Systems Engineer
I specialize in bridging the gap between **high-assurance security** and **resource-constrained embedded systems**. My work focuses on Post-Quantum Cryptography (PQC) migration, hardware-rooted trust, and real-time observability.

---

### Featured Projects

#### QuantumShield
**RTOS Middleware for PQC Migration** (https://github.com/viiavi/quantumshield)
- Designed a Zephyr-based middleware for runtime classical-to-PQC migration on nRF54L15 (Cortex-M33, TrustZone).
- Implements hybrid ML-KEM-768 + ECDH key exchange with a three-state transition engine persisted across reboots.
- Constraint-aware AI selector profiling RAM/flash/CPU at boot — validated on hardware achieving ML-KEM-768 keygen in 9ms at 128MHz.
- Selected for **Unisys Innovation Program Y17** among national submissions.

#### [RTOSTwin](https://github.com/viiavi/RTOSTwin)
**Embedded Runtime Observability Stack**
- A FreeRTOS telemetry pipeline for STM32 using UART DMA with delta encoding and CRC framing.
- Streams live task, heap, and CPU metrics to **Prometheus** and **Grafana**.
- Validated end-to-end achieving sub-2% CPU overhead and bounded WCET on STM32 hardware.

#### [Sugarcane IoT](https://github.com/viiavi/sugarcane_iot)
**Multi-Node Embedded Sensor Network**
- Multi-node IoT sensor network — STM32F303RE sensor node to STM32F401RE bridge over UART, forwarded via NodeMCU ESP8266 to ThingSpeak.
- Debugged hardware-level UART routing constraints, ADC channel isolation, and cross-board pin mapping differences between F303 and F401.

---

### Technical Arsenal

| Category | Tools & Technologies |
| :--- | :--- |
| **RTOS** | Zephyr RTOS, FreeRTOS |
| **Languages** | C, C++, Python |
| **Hardware** | nRF54L15 (Cortex-M33), STM32 (F3/F4), ESP8266, Nordic nRF Connect SDK |
| **Interfaces** | UART/SPI/I2C, BLE, DMA, JTAG/SWD |
| **Security** | FIDO2/CTAP2, PSA Crypto, TF-M, MCUboot, Post-Quantum Cryptography, ML-KEM-768, ML-DSA, Secure Boot, TrustZone |
| **Tools** | West, CMake, Ninja, STM32CubeIDE, J-Link, Git |
| **Observability** | Prometheus, Grafana, ThingSpeak |

---

### Connect with Me
- [Email](mailto:vainaviarunkumar@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/vainavi-arun-kumar-08ab53378)
- *Currently exploring the intersection of PQC and Trusted Execution Environments.*

---

<p align="center">
  <i>"Security is not a product, but a process."</i>
</p>
