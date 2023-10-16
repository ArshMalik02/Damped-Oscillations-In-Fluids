# Damped-Oscillations-In-Fluids

## Technology

- Data Analysis: Python (NumPy, Pandas, Matplotlib)
- Data Collection: Arduino (C++)

## Abstract

The aim of this report is to analyze the relationship between fluid viscosity and oscillation damping constant using a spring-mass system. We hypothesized that, if a mass on a spring oscillates in a fluid, the damping constant will decrease proportionally as the viscosity of the fluid increases. This is based on the knowledge that a fluid of higher viscosity will lead to more resistance against objects that flow through it. 


The mass in this experiment is a small cylindrical weight. An Arduino set-up with an ultrasonic sensor was used to record the displacement of the mass. The ultrasonic sensor sent out pulses, which were reflected off of a piece of cardboard at the top of the spring system. The fluids used include the control variable air, water, olive oil, and hand sanitizer gel. 

A best-fit function was created using least-squares in Python to represent oscillation for each data set. The resulting equations model sinusoidal motion with decreasing amplitude through each cycle. The average damping constant of each fluid was found using this function. The average of three trials was calculated for each data set to account for error. Comparing the viscosities of each fluid in Pascal-seconds, obtained from external sources, and their respective damping constants, we determined that the damping constant for a spring-mass oscillating system will decrease as viscosity increases.