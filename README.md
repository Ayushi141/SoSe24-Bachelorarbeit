# Bridging Model Theory and Machine Learning

**Bachelor's Thesis**

This thesis is directly inspired by:

> Chase, H., & Freitag, J. (2019). Model theory and machine learning. *Bulletin of Symbolic Logic*, 25(3), 319-332. [doi:10.1017/bsl.2019.20](https://doi.org/10.1017/bsl.2018.71)

We aim to provide a comprehensive exposition of the fundamental connections between model theory and machine learning theory, establishing rigorous proofs for the equivalences between logical stability properties and computational learning paradigms. Filling in the details in the paper of Chase and Freitag, we present detailed proofs and accessible explanations of two central results:

1. **NIP theories ↔ PAC learnable concept classes**
2. **Stable theories ↔ Online learnable concept classes**

The work bridges classical model-theoretic concepts with modern computational learning theory, making these deep connections accessible to students with basic knowledge in probability theory and model theory.

## Main Results

### Theorem 1: NIP ↔ PAC Learnability
**Statement:** A theory  is NIP if and only if every concept class definable in T is PAC learnable.

### Theorem 2: Stability ↔ Online Learnability  
**Statement:** A theory T is stable if and only if every concept class definable in T is online learnable.

## Structure

The thesis is organized as follows:

**Introduction** - Motivation and overview of the connections between model theory and machine learning

**Chapter 1: VC dimension and NIP theories**
- PAC learning framework and fundamental definitions
- The fundamental theorem of PAC learning (complete proof)
- VC dimension, shatter functions, and the Sauer-Shelah lemma
- ε-nets and the VC theorem
- NIP theories and the equivalence with finite VC dimension

**Chapter 2: Littlestone dimension and stable theories**  
- Online learning framework and mistake bounds
- Littlestone dimension and the Standard Optimal Algorithm (SOA)
- Stable theories and Shelah's 2-rank
- Equivalence between finite Littlestone dimension and stability

**Chapter 3: Further Research** - Directions for future work and open problems

## Prerequisites

This thesis assumes familiarity with:
- **Model Theory:** First-order logic, languages, structures, models and theories. Knowledge of key theorems such as the Löwenheim-Skolem theorem and compactness theorem is beneficial.
- **Probability Theory:** Probability spaces, measures, random variables, expectation, and basic concentration inequalities.

No prior knowledge of computational learning theory is assumed; all necessary concepts are developed from first principles with complete proofs.
