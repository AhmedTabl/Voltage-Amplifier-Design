**CE-CE-CC Amplifier Design Project**

This project focuses on designing a single-supply, multistage inverting amplifier using Bipolar Junction Transistors (BJTs) in a CE-CE-CC (Common Emitter-Common Emitter-Common Collector) configuration. The amplifier is optimized for specific performance requirements, including voltage gain, quiescent current, output swing, and frequency response.

**Key Features:**
- Multistage Amplification: Utilizes two Common Emitter (CE) stages for high voltage gain, followed by a Common Collector (CC) stage to achieve high input impedance, low output impedance, and unity voltage gain.
- Precise Specifications: Designed to operate under a +10V supply, limited to a maximum quiescent current of 10mA, and achieving a no-load voltage gain of 50 (±10%) at 1 kHz.
- Load Tolerance: Maintains at least 90% of the no-load voltage gain when subjected to a 1kΩ load, ensuring minimal performance degradation under different load conditions.
- Wide Frequency Response: Ensures consistent performance across a frequency range of 20Hz to 50kHz with a -3dB response at the boundaries.
- Simulation and Validation: The design was thoroughly tested and validated through simulations using Multisim, with analysis including input/output voltages, frequency response, and power efficiency.

**Design Goals:**
- Achieve a high voltage gain while maintaining efficiency and minimizing distortion.
- Ensure a broad frequency response suitable for a wide range of signal types.
- Use minimal components to meet the design constraints, including the use of only three BJTs, resistors, and capacitors from the E24 series.

**Simulation Tools:**
Multisim was used for DC sweep analysis, determining the operating point and load line, as well as simulating the input/output behavior under different load conditions.

**Results and Conclusion:**
The designed amplifier successfully met the specified requirements for gain, quiescent current, and frequency response. Minor discrepancies were noted between theoretical calculations and simulation results, likely due to rounding and simulation limitations. However, the amplifier consistently performed as expected across all tests.
