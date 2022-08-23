---
layout: default
---

## What is Lattice-based Cryptography?
- [Lattice-based Cryptography (Daniele Micciancio and Oded Regev)](https://cims.nyu.edu/~regev/papers/pqc.pdf)
- [Basic Lattice Cryptography: Encryption and Fiat-Shamir Signatures (Vadim Lyubashevsky)](https://drive.google.com/file/d/1JTdW5ryznp-dUBBjN12QbvWz9R41NDGU/view?usp=sharing)
- [Tutorial introduction to the security of lattice-based cryptosystems (Laarhoven et. al.)](https://eprint.iacr.org/2012/533.pdf)

## Courses and online lectures
- [Lattices, Learning with Errors and Post-Quantum Cryptography (Vinod Vaikuntanathan)](http://people.csail.mit.edu/vinodv/CS294/)
- [Lattices Algorithms and Applications (Daniele Micciancio)](https://cseweb.ucsd.edu/classes/fa21/cse206A-a/)
- [An Intensive Introduction to Cryptography (Boaz Barak)](https://intensecrypto.org/public/index.html)
- [Lattices in Cryptography (Chris Peikert)](https://web.eecs.umich.edu/~cpeikert/lic15/index.html)
- [Lattices in Computer Science (Oded Regev)](https://cims.nyu.edu/~regev/teaching/lattices_fall_2009/index.html)
- [BIU Winter School on Lattice-based Cryptography and Applications (Bar-Ilan University, 2012)](https://cyber.biu.ac.il/event/the-2nd-biu-winter-school/)
- [Workshop on Mathematics of Lattices and Cybersecurity (Brown University, 2015)](https://icerm.brown.edu/topical_workshops/tw15-7-mlc/#lecturevideos)
- [Spring School on Lattice-Based Cryptography (University of Oxford, 2017)](https://www.maths.ox.ac.uk/groups/cryptography/spring-school-lattice-based-cryptography)
- [Lattices: Algorithms, Complexity, and Cryptography (Simons Institute, 2020)](https://simons.berkeley.edu/programs/lattices2020)

## Surveys
- [A Decade of Lattice Cryptography (Chris Peikert)](https://eprint.iacr.org/2015/939.pdf)
- [Advances on quantum cryptanalysis of ideal lattices (Léo Ducas)](http://www.nieuwarchief.nl/serie5/pdf/naw5-2017-18-3-184.pdf)
- [Lattice Attacks on NTRU and LWE: A History of Refinements (Martin Albrecht and Léo Ducas)](https://eprint.iacr.org/2021/799)

## PhD theses
- [Design and Implementation of Lattice-Based Cryptography (Tancrède Lepoint, 2014)](https://tlepoint.github.io/phd/lepoint-phd-thesis.pdf)
- [Efficient Lattice-Based Zero-Knowledge Proofs and Applications (Rafaël del Pino, 2018)](https://tel.archives-ouvertes.fr/tel-02445482/document)
- [On ideal lattices and the GGH13 multilinear map (Alice Pellet--Mary, 2019)](https://apelletm.pages.math.cnrs.fr/page-perso/documents/articles/PhD_thesis.pdf)
- [Lattice-based Protocols for Privacy (Cecilia Boschini, 2020)](https://doc.rero.ch/record/328567/files/2020INFO002.pdf)
- [Practice-Oriented Techniques in Lattice-Based Cryptography (Muhammed F. Esgin, 2020)](https://bridges.monash.edu/articles/thesis/Practice-Oriented_Techniques_in_Lattice-Based_Cryptography/12279728)
- [Extended Security of Lattice-based Cryptography (Mélissa Rossi, 2020)](https://www.di.ens.fr/~mrossi/docs/thesis.pdf)
- [Practical lattice-based cryptography over structured lattices (Sarah McCarthy, 2020)](https://pureadmin.qub.ac.uk/ws/portalfiles/portal/211831925/thesis.pdf)
- [Efficiency and security aspects of lattice-based cryptography (Carl Bootland, 2021)](https://www.esat.kuleuven.be/cosic/publications/thesis-399.pdf)
- [Post-Quantum Cryptography: Cryptanalysis and Implementation (Fernando Vidria, 2021)](https://fundamental.domains/2021virdiafphd.pdf)

## Other resources
- [Collection of resources and links maintained by Daniele Micciancio](https://cseweb.ucsd.edu/~daniele/LatticeLinks/index.html)
- [Workshop on Lattices with Symmetry (University of California, Irvine, 2013)](https://www.math.uci.edu/~asilverb/Lattices/)
- [Computational Challenges in the Theory of Lattices (Brown University, 2018)](https://icerm.brown.edu/programs/sp-s18/w4/)
- [Mathematical Foundations of Asymmetric Cryptography (French Mathematical Society, 2019)](https://mathsofpkc.sciencesconf.org/resource/page/id/1)

## Reading groups and seminars open to the public
- [Monash Cybersecurity Seminars](https://www.monash.edu/it/ssc/cybersecurity/seminars)

## Lattice-based primitives selected by NIST for standardization

| Name | Primitive | Description |
| :----------- | :------- | :------- |
| CRYSTALS-KYBER     | PKE & KEM         | [Official site](https://pq-crystals.org/kyber/)|
| CRYSTALS-DILITHIUM | Digital signature | [Official site](https://pq-crystals.org/dilithium/)|
| FALCON             | Digital signature | [Official site](https://falcon-sign.info/) |


## Implementations of cryptographic primitives

| Name | Language | Author |
| :---------- | :--- | :------- |
| [CRYSTALS-KYBER](https://github.com/pq-crystals/kyber) | C  | Official  |
| [CRYSTALS-KYBER](https://github.com/symbolicsoft/kyber-k2so) | Go  | Symbolic Software  |
| [CRYSTALS-KYBER](https://github.com/antontutoveanu/crystals-kyber-javascript) | JavaScript  | Anton Tutoveanu  |
| [CRYSTALS-KYBER](https://github.com/bcgit/bc-java/tree/master/core/src/main/java/org/bouncycastle/pqc/crypto/crystals/kyber) | Java  | Legion of the Bouncy Castle Inc. |
| [CRYSTALS-DILITHIUM](https://github.com/pq-crystals/dilithium) | C  | Official |
| [CRYSTALS-DILITHIUM](https://github.com/bcgit/bc-java/tree/master/core/src/main/java/org/bouncycastle/pqc/crypto/crystals/dilithium) | Java  | Legion of the Bouncy Castle Inc. |
| [FALCON](https://falcon-sign.info/impl/falcon.h.html) | C  | Official |
| [FALCON](https://github.com/tprest/falcon.py) | Python  | Thomas Prest |
| [FALCON](https://github.com/bcgit/bc-java/tree/master/core/src/main/java/org/bouncycastle/pqc/crypto/falcon) | Java  | Legion of the Bouncy Castle Inc. |
| [FALCON](https://github.com/bcgit/bc-csharp/tree/master/crypto/src/pqc/crypto/falcon) | C#  | Legion of the Bouncy Castle Inc. |
| [FRODO](https://github.com/Microsoft/PQCrypto-LWEKE) | C  | Official |
| [FRODO](https://github.com/mariiatuzovska/frodo) | Go  | Mariia Tuzovska |
| [FRODO](https://github.com/bcgit/bc-java/tree/master/core/src/main/java/org/bouncycastle/pqc/crypto/frodo) | Java  | Legion of the Bouncy Castle Inc. |
| [FRODO](https://github.com/bcgit/bc-csharp/tree/master/crypto/src/pqc/crypto/frodo) | C#  | Legion of the Bouncy Castle Inc. |
| [NTRU](https://github.com/prokls/ntrust-native) | Rust  | Lukas Prokop |
| [NTRU](https://github.com/bcgit/bc-java/tree/master/core/src/main/java/org/bouncycastle/pqc/crypto/ntru) | Java  |  Legion of the Bouncy Castle Inc.  |
| [NTRU](https://github.com/bcgit/bc-csharp/tree/master/crypto/src/pqc/crypto/ntru) | C#  |  Legion of the Bouncy Castle Inc.  |
| [NTRU Prime](https://github.com/bcgit/bc-java/tree/master/core/src/main/java/org/bouncycastle/pqc/crypto/ntruprime) | Java  |  Legion of the Bouncy Castle Inc.  |
| [NTRU Prime](https://github.com/bcgit/bc-csharp/tree/master/crypto/src/pqc/crypto/ntruprime) | C#  |  Legion of the Bouncy Castle Inc.  |
| [SABER](https://github.com/lkiem/rusty_saber) | Rust  | Lukas Prokop & Lukas Kiem |
| [SABER](https://github.com/bcgit/bc-java/tree/master/core/src/main/java/org/bouncycastle/pqc/crypto/saber) | Java  | Legion of the Bouncy Castle Inc. |
| [SABER](https://github.com/bcgit/bc-csharp/tree/master/crypto/src/pqc/crypto/saber) | C#  | Legion of the Bouncy Castle Inc. |

## Security estimation tools
- [Lattice estimator](https://github.com/malb/lattice-estimator/)
- [Leaky LWE estimator (Dachman-Soled et. al.)](https://github.com/lducas/leaky-LWE-Estimator)

<!--
## Standardization efforts and updates on NIST's competition

- [TODO](./another-page.html).
-->

## Lattice.bib

We provide a .bib file with references to lattice-based cryptography papers. Find it [here](https://github.com/octaviopk9/lattice-based-cryptography/blob/main/lattices.bib).

## About this page

This page is based on [zkp.science](https://zkp.science/)'s page, which hosts a number of resources and references on Zero-Knowledge Proofs. Everyone is welcome to contribute to this effort. Additions, corrections and other suggestions are very much welcome!

## How to improve this page

 You can propose an edit to this page [here](https://github.com/octaviopk9/lattice-based-cryptography). (Note that after making your edits, there are 3 confirmations to click through in order to create the "pull request" in the Git repository underlying this page.)

For more broad changes, you can make a pull request [here](https://github.com/octaviopk9/lattice-based-cryptography)!

If you don't feel confident or skilled to directly contribute through github, please feel free to reach out any of the existing contributors with your ideas and comments on how to improve this page.
