# Mini-Blockchain

This demonstration of a Proof-of-Work blockchain shows how hashing provides immutability and security for the blockchain.

Each block contains its own hash and the hash of the previous block. A hash function takes an input and produces a fixed length output unique to the input. A small change of just a single character in the input will completely change output hash.

If an attacker attempts to alter a past block, its hash changes and breaks the chain as the subsequent block no longer contains the correct hash of the previous. 

## How to run:
### Dependiencies: Node.js

With your terminal opened to the directory containing blockchain_v1.js enter:

    node blockchain_v1.js

## Screenshots
<img width="1070" height="488" alt="Screenshot 2025-09-07 at 11 18 52 PM" src="https://github.com/user-attachments/assets/253a65a0-c30c-49d0-a7f3-707fb86a7d2c" />


<img width="623" height="138" alt="Screenshot 2025-09-07 at 11 19 10 PM" src="https://github.com/user-attachments/assets/5694237b-3907-4538-a1aa-ba36b7ceb67c" />
