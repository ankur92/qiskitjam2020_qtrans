# qiskitjam2020_qtrans
This repository will be used to maintian the code for QISKIT Summer Jam 2020.

Secure transmission of information is one of the remarkable features of quantum communication. Unlike the classical encryption algorithm, which always has a finite probability of being cracked, superdense coding provides a way to transmit information securely along with the additional advantage of enhanced channel capacity. The information is stored in the correlation (entanglement) and not locally on any of the qubits. Consequently, an eavesdropper, by intercepting the qubit(s) en route, will not only fail to obtain any information but also leave behind a telltale sign of tampering activity. 
In this project, we implement two schemes utilizing two Bell pairs and one GHZ state as the transmission channel. We transmit a picture and a text message on a 5-qubit quantum processor using the Qiskit package. The average success rates of a single transmission are 55% and 76% with the Bell and GHZ states respectively, which are further improved by using a classical error-correction scheme (majority vote). Our results show that the GHZ channel performs better for faithful transmission.
