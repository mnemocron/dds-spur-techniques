# dds-spur-techniques
Paper draft in Jupyter notebook comparing spurious improvement techniques

---

## Simulation and Comparison of Spurious Reduction Methods for DDS
### A quantitative analysis using simulation in Python

*Abstract* - With the performance increase of high frequency digital to analog converters, digital synthesizers continue to replace traditional analog oscillator circuits. Traditional Direct Digital Synthesizers (DDS) use ROM lookup tables to convert phase to (sinusoidal) amplitude. The phase truncation occurring in this architecture seriously limits the spectral performance of the generated signal in the form of spurs. This work uses MATLAB/Simulink to reproduce the frequency errors widely discussed in literature. The simulation framework is then used to apply various amplitude treatement algorithms to correct the signal and improve the spurious performance. Furthermore, the algorithms are compared against each other to ﬁnd the best method in terms of spurious free dynamic range (SFDR), consumed hardware resources on FPGA and latency. The proposed design includes an 8 channel polyphase DDS with linear interpolation correction and an expected SFDR of below −105 dBc.

*Keywords* - Direct Digital Synthesis, Bit True Simulation, Spurious Performance Analysis, High Frequency Signal Generation
