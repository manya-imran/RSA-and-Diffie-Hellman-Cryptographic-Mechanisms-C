# RSA-and-Diffie-Hellman-Cryptographic-Mechanisms-C
This project implements the RSA and Diffie Hellman Algorithm from scratch in C++

Two peer’s (peer-1 and peer-2) wants securely communicate between each other.
This should be done into three phases, which are shown in the diagram below:

<img width="538" alt="image" src="https://github.com/manya-imran/RSA-and-Diffie-Hellman-Cryptographic-Mechanisms-C/assets/167977645/c7eedc3b-01fd-4b90-a015-6f07707a505d">



1. In Phase-1: both peers generate their own RSA key pairs (Public and private
keys)

2. In Phase-2: both peers share their public keys securely by using Diffie-Hellman
key exchange mechanism.

4. In Phase-3: both peers securely communicate with each other by using RSA
keys. We can do it by sending a text file securely between the peers.
