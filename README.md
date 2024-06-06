# Underwater-optical-wireless-communication
**Description:**

This project investigates the performance of an Underwater Optical Wireless Communication (UOWC) system under varying channel conditions using OptiSystem, a software for simulating optical communication links. UOWC offers significant advantages over traditional acoustic methods, including higher bandwidth, lower latency, and potentially lower power consumption (for shorter ranges).

**Modulator Design:** This project analyzes the impact of two modulators on UOWC system performance:

* Amplitude Modulator (AM): This basic modulator varies signal intensity based on the information to be transmitted.
* Mach-Zehnder Modulator (MZM): This advanced modulator manipulates the phase and/or intensity of light for more complex modulation schemes.

**OptiSystem Simulation:**  OptiSystem is used to create a realistic model of the UOWC channel, incorporating three types of water environments:

* Clean Water: Represents low-turbidity conditions with minimal absorption and scattering.
* Coastal Ocean: Simulates a more challenging environment with moderate levels of absorption and scattering due to plankton and other particles.
* Turbid Harbor: Models a highly turbid environment with significant absorption and scattering, presenting the most challenging scenario for UOWC.
  
**450nm Laser:** 

The project analyzes system performance using a 450nm laser source, a common choice for UOWC due to its balance between penetration depth and absorption.

**Performance Evaluation:** The project evaluates the system's performance using key metrics:

* Bit Error Rate (BER): This metric indicates the percentage of bits incorrectly received, with a lower BER signifying better performance.
* Quality Factor (Q-factor): This metric relates to the signal-to-noise ratio (SNR) and BER, providing insights into the overall system reliability.
