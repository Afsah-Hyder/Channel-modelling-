#  Communication System Simulation and Analysis
This project investigates the impact of various channel models on communication systems and explores equalization techniques to mitigate channel distortion. We simulate different channel conditions (AWGN, fading channels) and impairments (phase noise, frequency offset) using Simulink. We then implement linear (zero-forcing, MMSE) and nonlinear (decision feedback) equalization techniques to improve signal quality. The project evaluates system performance through Bit Error Rate (BER) analysis, eye diagrams, constellation diagrams, and SNR vs. BER curves.

## Project Structure

### Simulink Models
* Channel Models (AWGN, Rayleigh, Rician fading) with impairments
* Equalization Techniques (linear and nonlinear)

### Data Analysis Scripts
* BER calculations
* Eye diagram generation
* Constellation diagram plotting
* SNR vs. BER curve creation

## Reference
[Multipath Fading Channel](https://www.mathworks.com/help/comm/ug/multipath-fading-channel-1.html)
(We used this resource as a starting point for understanding multipath fading channels)

