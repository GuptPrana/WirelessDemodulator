# E4110 - 16-QAM Signal Demodulator Block Design

In this simulation, the I/Q data samples are generated from the transmitter baseband, mapped to
modulation symbol via pulse shaping filter (root raised cosine) and transmitted over a
flat fading channel. This project builds the demodulator block to classify the received symbols into information bits.

For M-QAM, the signal space is two dimensional and hence, it is
convenient to represent a constellation point (a member of the signal set) as a complex
number. The real part of the number denotes the x-coordinate (In-phase) and the imaginary part of the number denotes
the y-coordinate (Quadrature) of the constellation point. Hence, the signal set of 16-QAM is represented
by 16 complex points on the I-Q space.

Key Tasks:
- Design the Demodulator Block
- Explain the theory behind the design and the performance in Simulink
- Pick a practical WiFi system and elaborate the physical layer frame format and the function of each fields in the frame.
- Elaborate the top-level architecture of the transmitter and the receiver of the WiFi system.

Report: 16_QAM_Demodulator.pdf