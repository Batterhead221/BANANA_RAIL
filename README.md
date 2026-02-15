# BANANA_RAIL

A real ugly but compact fixed-output bench power supply PCB designed for prototyping, and breadboard power. 
Rev A — Functional prototype
Designed for 1A output applications (Arduino, ESP32, sensors, logic circuits)


1A LM2596-based buck converter board with:
	•	+5V output
	•	+3.3V output (post-regulated)
	•	Dedicated GND banana terminal
	•	On-board rocker power switch
	•	Reverse polarity protection
	•	Large high-current copper pours
	•	PCB-mounted banana jack outputs for direct lab use


Designed as a clean, beginner-friendly power module for bench setups instead of breadboard regulators.


Key Features
	•	Input: DC barrel jack (≈ 7–24V recommended)
	•	Outputs:
	•	+5V (primary buck output)
	•	+3.3V rail
	•	GND reference terminal
	•	Output connectors: PCB soldered banana jacks (Pomona-style footprint)
	•	Rated current: ~1A continuous
	•	Switching regulator: LM2596
	•	Thick traces optimized for low voltage drop
	•	Full ground plane (B.Cu pour) with stitching vias


Design Notes
	•	Layout prioritizes short switching loops around U1, L1, and D2
	•	High-current paths use wide copper pours for thermal and electrical stability
	•	Output rails routed directly to banana terminals for bench-friendly wiring
	•	Footprints created/customized in KiCad for mechanical robustness
	•	Banana jacks are objectively cooler
	•	Custom footprint designs

Designed and engineered by Brandon Shelly
