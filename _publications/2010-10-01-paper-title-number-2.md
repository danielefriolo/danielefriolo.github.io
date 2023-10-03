---
title: "Multi-key and multi-input predicate encryption from learning with errors"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
date: 2022-10-01
venue: 'EUROCRYPT 22'
paperurl: 'https://eprint.iacr.org/2022/806.pdf'
citation: 'Francati, D., Friolo, D., Malavolta, G., & Venturi, D. (2023, April). Multi-key and multi-input predicate encryption from learning with errors. In Annual International Conference on the Theory and Applications of Cryptographic Techniques (pp. 573-604). Cham: Springer Nature Switzerland.'
---
We put forward two natural generalizations of predicate encryption (PE), dubbed multi-key and multi-input PE. More in details, our contributions are threefold.

- Definitions. We formalize security of multi-key PE and multi-input PE following the standard indistinguishability paradigm, and modeling security both against malicious senders (i.e., corruption of encryption keys) and malicious receivers (i.e., collusions).

- Constructions. We construct adaptively secure multi-key and multi-input PE supporting the conjunction of poly-many arbitrary single-input predicates, assuming the sub-exponential hardness of the learning with errors (LWE) problem.

- Applications. We show that multi-key and multi-input PE for expressive enough predicates suffices for interesting cryptographic applications, including non-interactive multi-party computation (NI-MPC) and matchmaking encryption (ME).

In particular, plugging in our constructions of multi-key and multi-input PE, under the sub-exponential LWE assumption, we obtain the first ME supporting arbitrary policies with unbounded collusions, as well as robust (resp. non-robust) NI-MPC for so-called all-or-nothing functions satisfying a non-trivial notion of reusability and supporting a constant (resp. polynomial) number of parties. Prior to our work, both of these applications required much heavier tools such as indistinguishability obfuscation or compact functional encryption.

[Download paper here](https://eprint.iacr.org/2022/806.pdf)

Recommended citation: Francati, D., Friolo, D., Malavolta, G., & Venturi, D. (2023, April). Multi-key and multi-input predicate encryption from learning with errors. In Annual International Conference on the Theory and Applications of Cryptographic Techniques (pp. 573-604). Cham: Springer Nature Switzerland.
