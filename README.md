# Accelerating Polarization via Alphabet Extension

I. Duursma, R. Gabrys, V. Guruswami, T.-C. Lin, H.-P. Wang.
*Accelerating Polarization via Alphabet Extension*.
International Conference on Randomization and Computation (RANDOM).
September 2022.

DOI is <https://doi.org/10.4230/LIPIcs.APPROX/RANDOM.2022.17>

Full version is <https://arxiv.org/abs/2207.04522>

Animation is on <https://www.youtube.com/watch?v=2mmbd58rSts>

## Abstract

Polarization is an unprecedented coding technique in that it not only achieves channel capacity, but also does so at a faster speed of convergence than any other technique. This speed is measured by the "scaling exponent" and its importance is three-fold. Firstly, estimating the scaling exponent is challenging and demands a deeper understanding of the dynamics of communication channels. Secondly, scaling exponents serve as a benchmark for different variants of polar codes that helps us select the proper variant for real-life applications. Thirdly, the need to optimize for the scaling exponent sheds light on how to reinforce the design of polar code. In this paper, we generalize the binary erasure channel (BEC), the simplest communication channel and the protagonist of many polar code studies, to the "tetrahedral erasure channel" (TEC). We then invoke Mori-Tanaka’s 2 × 2 matrix over 𝔽_4 to construct polar codes over TEC. Our main contribution is showing that the dynamic of TECs converges to an almost-one-parameter family of channels, which then leads to an upper bound of 3.328 on the scaling exponent. This is the first non-binary matrix whose scaling exponent is upper-bounded. It also polarizes BEC faster than all known binary matrices up to 23 × 23 in size. Our result indicates that expanding the alphabet is a more effective and practical alternative to enlarging the matrix in order to achieve faster polarization.

## Remarks

This is the Jupyter notebook that I use to compile Manim animations.
