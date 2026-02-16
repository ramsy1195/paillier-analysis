# Paillier Cryptosystem – Mathematical Analysis and Hybrid Encryption Design

This repository contains my research paper analyzing the Paillier cryptosystem from both a mathematical and applied cryptography perspective. The work explores the number‑theoretic foundations of Paillier, demonstrates its encryption and decryption processes, evaluates its security guarantees, and proposes an improved hybrid encryption scheme that integrates Paillier with AES for practical, CCA‑resistant secure communication.

## Paper
**paillier_hybrid_encryption_paper.pdf**  
A 3–5 page research paper covering:

- A rigorous mathematical derivation of Paillier’s correctness using the Decisional Composite Residuosity Assumption (DCRA), Euler’s theorem, and modular arithmetic over $\( \mathbb{Z}_{n^2} \)$.
- A full worked example encrypting and decrypting the message “MATH,” including randomness selection and ciphertext computation.
- A security analysis discussing semantic security, homomorphic properties, vulnerabilities, and a brute‑force attack demonstration.
- A proposed **hybrid Paillier + AES encryption system** that mitigates Paillier’s CCA vulnerabilities and inefficiency for large messages.
- A Python implementation (included as screenshots in the paper) demonstrating the hybrid scheme in practice.

## Summary of Contributions
- **Hybrid System Design:** Introduces a Paillier‑AES hybrid encryption model combining asymmetric key encapsulation with symmetric authenticated encryption for improved efficiency and security.
- **Mathematical Proofs:** Provides a clear, step‑by‑step derivation of Paillier’s decryption formula and correctness.
- **Security Evaluation:** Analyzes vulnerabilities such as randomness reuse, small‑modulus attacks, and CCA exposure.
- **Applied Cryptography:** Implements encryption, decryption, and attack simulations in Python to validate theoretical claims.

## Topics Covered
- Public‑key cryptography  
- Homomorphic encryption  
- Number theory (modular arithmetic, Euler’s theorem, L‑function)  
- Decisional Composite Residuosity Assumption (DCRA)  
- Hybrid encryption (Paillier + AES)  
- Security analysis and attack modelling  

---

If you have questions about the paper or want to discuss cryptography, feel free to reach out!
