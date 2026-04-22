# IOt-individualProject

This project implements an IoT-based signal processing system on an ESP32 that dynamically adapts its sampling frequency based on the characteristics of the input signal. The system performs local computation using FFT (Fast Fourier Transform) to identify dominant frequencies and reduces unnecessary data transmission by computing aggregated values.

Instead of relying on external sensors, the system uses a mathematically simulated signal, enabling controlled testing of sampling strategies, noise behavior, and frequency detection accuracy.

⸻

🎯 Objectives
	•	Generate and process a continuous-time signal s(t)
	•	Apply FFT to extract dominant frequency components
	•	Dynamically adapt sampling frequency using Nyquist criteria
	•	Compute aggregate statistics over time windows
	•	Demonstrate edge computing by reducing transmitted data
