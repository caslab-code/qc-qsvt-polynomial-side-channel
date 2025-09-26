# Recovering QSVT Polynomials from Side-Channel Information on Quantum Computers

The notebooks in this repository demonstrate conversion of Chebyshev polynomials to phase angles needed to realize the QSVT computation utilized in three QSVT functions: matrix inversion, cubic function, and amplitude amplification from Grover's search. The notebooks further provide functionality to introduce noise into the QSVT polynomial coefficients and then generate new, noisy phase angles. These original and noisy phase angles are used to evaluate the threat of side-channel attacks on QSVT. The notebooks show how even with added noise, the coefficients are unique to each QSVT function: matrix inversion, cubic function, and amplitude amplification from Grover's search. This demonstrate that attacker, who can obtain such coefficents through side-channels, could guess the type of QSVT function being computed. The code further includes simple notebook for classification of the phase angles that attacker could use to classify if the angles they observe most closely match matrix inversion, cubic function, or amplitude amplification from Grover's search.

# Research Paper Citation

Kidus Tessma, Hrvoje Kukina, and Jakub Szefer, "Recovering QSVT Polynomials from Side-Channel Information on Quantum Computers", in International Conference on Computer Design (ICCD), November 2025.

Kidus Tessma contributed to this paper as part of a project in the Secure Quantum Computing course at Northwestern University.

This work was supported in part by NSF grant 2332406.

# Code License

TBD

# Text and Image Copyright

The text Python notebooks is copyrighted by Kidus Tessma and Jakub Szefer, Sept. 2025.

#  Contact

All questions, improvementns, and suggestions can be sent to Jakub Szefer <jakub.szefer@northwestern.edu>
