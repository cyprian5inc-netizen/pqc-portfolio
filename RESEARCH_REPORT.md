\# Post-Quantum Cryptography Research Report



\*\*Author:\*\* Cyprian  

\*\*Date:\*\* July 2026  

\*\*Portfolio:\*\* \[pqc-portfolio](https://github.com/cyprian5inc-netizen/pqc-portfolio)



\## Executive Summary

This report documents initial explorations into Post-Quantum Cryptography, focusing on NIST candidates Kyber (KEM) and Dilithium (signatures).



\## 1. Introduction

Quantum computers threaten current public-key cryptography (RSA, ECC). PQC aims to replace them.



\## 2. Benchmarks



\### Key Encapsulation (Kyber)

\- Average time: \~0.03 ms (simulation)

\- Security Levels tested: L1, L3, L5



\### Digital Signatures (Dilithium proxy)

\- Average sign+verify time: \~X ms

\- Signature size: \~X bytes



\## 3. Comparison Table

(See `pqc\_benchmark\_results.csv`)



\## 4. Challenges \& Learnings

\- Library installation difficulties with native dependencies

\- Performance measurement on classical hardware

\- Importance of constant-time implementations



\## 5. Future Work

\- Real liboqs integration

\- Hybrid crypto schemes (classical + PQC)

\- IoT device testing

\- Side-channel attack resistance



\## References

\- NIST PQC Standardization

\- Open Quantum Safe (liboqs)

