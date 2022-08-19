---
layout: default
---

## What is Lattice-based Cryptography?
- [A Decade of Lattice Cryptography (Chris Peikert)](https://eprint.iacr.org/2015/939.pdf)
- [Lattice-based Cryptography (Daniele Micciancio and Oded Regev)](https://cims.nyu.edu/~regev/papers/pqc.pdf)
- [Basic Lattice Cryptography: Encryption and Fiat-Shamir Signatures (Vadim Lyubashevsky)](https://drive.google.com/file/d/1JTdW5ryznp-dUBBjN12QbvWz9R41NDGU/view?usp=sharing)
- [Tutorial introduction to the security of lattice-based cryptosystems (Laarhoven et. al.)](https://eprint.iacr.org/2012/533.pdf)

## Courses, online lectures and resources pages
- [Lattices, Learning with Errors and Post-Quantum Cryptography (Vinod Vaikuntanathan)](http://people.csail.mit.edu/vinodv/CS294/)
- [Lattices Algorithms and Applications (Daniele Micciancio)](https://cseweb.ucsd.edu/classes/fa21/cse206A-a/)
- [Collection of resources and links maintained by Daniele Micciancio](https://cseweb.ucsd.edu/~daniele/LatticeLinks/index.html)
- [An Intensive Introduction to Cryptography (Boaz Barak)](https://intensecrypto.org/public/index.html)
- [Lattices in Cryptography (Chris Peikert)](https://web.eecs.umich.edu/~cpeikert/lic15/index.html)
- [Lattices in Computer Science (Oded Regev)](https://cims.nyu.edu/~regev/teaching/lattices_fall_2009/index.html)
- [BIU Winter School on Lattice-based Cryptography and Applications (Bar-Ilan University, 2012)](https://cyber.biu.ac.il/event/the-2nd-biu-winter-school/)
- [Workshop on Mathematics of Lattices and Cybersecurity (Brown University, 2015)](https://icerm.brown.edu/topical_workshops/tw15-7-mlc/#lecturevideos)
- [Spring School on Lattice-Based Cryptography (University of Oxford, 2017)](https://www.maths.ox.ac.uk/groups/cryptography/spring-school-lattice-based-cryptography)
- [Lattices: Algorithms, Complexity, and Cryptography (Simons Institute, 2020)](https://simons.berkeley.edu/programs/lattices2020)

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

## Reading groups and seminars open to the public
- [Monash Cybersecurity Seminars](https://www.monash.edu/it/ssc/cybersecurity/seminars)

## Lattice-based primitives selected by NIST for standardistation

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
| [CRYSTALS-DILITHIUM](https://github.com/pq-crystals/dilithium) | C  | Official |
| [FALCON](https://falcon-sign.info/impl/falcon.h.html) | C  | Official |
| [FALCON](https://github.com/tprest/falcon.py) | Python  | Thomas Prest |
| [FRODO](https://github.com/Microsoft/PQCrypto-LWEKE) | C  | Official |
| [FRODO](https://github.com/mariiatuzovska/frodo) | Go  | Mariia Tuzovska |
| [NTRU](https://github.com/prokls/ntrust-native) | Rust  | Lukas Prokop |
| [SABER](https://github.com/lkiem/rusty_saber) | Rust  | Lukas Prokop & Lukas Kiem |

## Evaluation tools
- [LWE estimator (Albrecht et. al.)](https://lwe-estimator.readthedocs.io/)
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