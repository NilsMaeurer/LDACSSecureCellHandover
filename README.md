# The LDACS Secure Ground Handover Protocol

Formal Security Verification of the LDACS Secure Ground Handover Protocol

## Authors: 

Nils Mäurer, Thomas Gräupl: Institute of Communication and Navigation, German Aerospace Center (DLR), Wessling, Germany

Corinna Schmitt, Gabi Dreo Rodosek: Research Institute CODE, Universität der Bundeswehr München, Neubiberg, Germany

## **Paper**
- Nils Mäurer, Thomas Gräupl, Corinna Schmitt, "A Secure Ground Handover Protocol for LDACS", in: 7th ENRI International Workshop on ATM/CNS, IWAC 2022, Tokyo, Japan, pp. 1-10, Oktober 2022.

## **File structure:**
- src
  - proof_a_preq.spthy: Proof for DHKE based key establishment with GS2 certificate stored locally at AS
  - proof_b_preq.spthy: Proof for DHKE based key establishment GS2 sending its certificate alongside an OCSP response to the AS
  - proof_a_pqc.spthy:  Proof for KEM based key establishment with GS2 certificate stored locally at AS
  - proof_b_pqc.spthy:  Proof for KEM based key establishment GS2 sending its certificate alongside an OCSP response to the AS
  
## The Tamarin prover repository

For installation and usage instructions of the Tamarin prover see chapter 2 of the manual:

https://tamarin-prover.github.io/manual/book/002_installation.html

## Build environment

Tamarin prover: v1.6.1

OS: Windows 10 with WSL 2.0 - Ubuntu 20.04

Configuration: Intel(R) Core(TM) i7-8850U CPU 64GB of RAM

Verification time: ~2m 