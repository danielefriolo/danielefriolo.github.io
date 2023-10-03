---
title: "Registered (Inner-Product) Functional Encryption"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
venue: 'ASIACRYPT'
date: 2023-10-01
paperurl: 'https://eprint.iacr.org/2023/395.pdf'
citation: 'Francati, D., Friolo, D., Maitra, M., Malavolta, G., Rahimi, A., & Venturi, D. (2023). Registered (Inner-Product) Functional Encryption. ASIACRYPT 2023 (To appear)'
---

Registered encryption (Garg et al, TCC'18) is an emerging  paradigm that tackles the key-escrow problem associated with identity-based encryption by replacing the private-key generator with a much weaker entity known as the key curator. The key curator holds no secret information, and is responsible to: 
(i) update the master public key whenever a new user registers its own public key to the system;
(ii) provide helper decryption keys to the  users already registered in the system, in order to still enable them to decrypt after new users join the system.
For practical purposes, tasks (i) and (ii) need to be efficient, in the sense that the size of the public parameters, of the master public key, and of the helper decryption keys, as well as the running times for key generation and user registration, and the number of updates, must be small.

In this paper, we generalize the notion of registered encryption to the setting of functional encryption (FE). As our main contribution, we show an efficient construction of registered FE for the special case of (attribute-hiding) inner-product predicates, built over asymmetric bilinear groups of prime order. Our scheme supports a  attribute universe and is proven secure in the bilinear generic group model. We also implement our scheme and experimentally demonstrate the efficiency requirements of the registered settings. Our second contribution is a feasibility result where we build registered FE for P/Poly  based on indistinguishability obfuscation and somewhere statistically binding hash functions.

[Download paper here](https://eprint.iacr.org/2023/395.pdf)

Recommended citation: Francati, D., Friolo, D., Maitra, M., Malavolta, G., Rahimi, A., & Venturi, D. (2023). Registered (Inner-Product) Functional Encryption. ASIACRYPT 2023 (To appear).
