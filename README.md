# Implementing Lock-in detection using ExpEYES

Lock-in detection, the popular signal processing technique, is renowned for its ability to extract weak signals from noise. Lock-in amplifiers are widely used in numerous optical equipment and experimental configurations to detect weak signals superimposed on a noisy background. This motivates us to implement a Lock-in amplifier using the advantages of the ExpEYES-17 hardware and the growing computational
power of Python programming software.

The implementation includes the measurement of the amplitude and phase of the expected component of the signal specified by the reference signal. We also implement two variations, which use a sin reference signal and a square reference signal. The implementation is then tested using two common experiments: measurement of low resistance and measurement of mutual inductance. A comparison with the theoretical values is also made to validate the implementation. The results show that the implementation is able to measure the amplitude with very high accuracy and phase with reasonable accuracy.

Report available at: [Lock-in Detection using ExpEYES](LOCKIN.pdf)