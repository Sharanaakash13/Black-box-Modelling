# Black-box System Modelling

This Matlab live script is an implementation of system identification for an LTI (Linear Time-Invariant) model using a PRBS (Pseudo-Random Binary Sequence) input signal.

* The code starts by choosing an appropriate sampling time, based on the rise time of the system, and then generates a PRBS input signal with specified parameters.
* The system output is obtained by simulating a simple mechanical system using the input signal, and the resulting data is split into estimation and validation sets for model training and evaluation.
* This script uses the following model structure and residual are analysed for every model: 
              ARX model
Transfer function
Process model 
State space
*  The LTI model is then identified using the estimation data and validated using the validation data.
*  The code includes detailed comments for each step of the process.
