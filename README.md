# CoherentErrors_IBM
Detecting the amount of coherent error in IBM quantum processors Quito and logos


# Characterizing Coherent Errors in IBM Quito backend and lagos backend


The starting point of the investigation of the amount of coherent error and incoherent error on IBM quantum computer is by implementing Pulse inverse technique.

<p align="center">
<img width="750" alt="plcnot" src="https://github.com/Mojahed91/QuantumFourierT/assets/129369338/8f8cd236-f996-4426-8985-c43d7e22013b">
<p/>

Next, we create the circuits as depicted in the following figures, where we substitute the "k" with a CNOT gate and "k_i" with the inverse of a CNOT gate, implemented through a pulse inversion. We used six cycles.


<p align="center">

<img width="1138" alt="kik_cyc" src="https://github.com/Mojahed91/QuantumFourierT/assets/129369338/c9f7644d-0901-4f2d-8977-41c67d597a94">
<p/>

<p align="center">

<img width="1261" alt="rckik" src="https://github.com/Mojahed91/QuantumFourierT/assets/129369338/02b73034-0d7d-4bce-8917-2b462a67fa8c">
<p/>

## Here are the main results of the experimental implementation
<p align="center">

<img width="1142" alt="ert" src="https://github.com/Mojahed91/QuantumFourierT/assets/129369338/e516c662-1988-40f8-9fef-a464f4dd77eb">
<p/>

## References
1- [Master thesis Mojahed](https://www.overleaf.com/read/ctxdfjzkqjnw)

