# Readout-Error-Mitigation

We consider a simple 2-qubit circuit.

Create a custom noise model with the readout errors from one of the IBM backend avialbe to the public

Apply the following methods to mitigate the results:

1. complete_meas_cal method
2. measurement filter object 

Following are steps performed to mitigate the readout / measurement errors:
Step 1: Generate the calibration circuits 

Step 2: Generate the calibration matrix

Step 3: Create a noise model for the real backend: ibmq_quito using ibmq provider

Step 4: Generate the calibration matrix of the custom noise model with readout errors

Step 5:  Create the measurement filter object .Apply the results to the filter and get the mitigated counts

Step 6: Compare the noisy results and mitigated results


## REFERENCES:

https://qiskit.org/textbook/ch-quantum-hardware/measurement-error-mitigation.html

https://qiskit.org/documentation/stable/0.19/tutorials/noise/3_measurement_error_mitigation.html

Refer to backend properties :https://quantum-computing.ibm.com/lab/docs/iql/manage/systems/properties

https://learn.qiskit.org/summer-school/2020/superconducting-qubits-ii-circuit-electrodynamics-readout-calibration-methods
