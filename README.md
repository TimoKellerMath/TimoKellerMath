I do research in (computational) arithmetic geometry.

[Homepage](https://www.timo-keller.de/) · [Publications](https://www.timo-keller.de/publications.html) · [Blog](https://www.timo-keller.de/blog/)

## Code for my papers

### Birch–Swinnerton-Dyer conjecture

- Complete verification of strong BSD for many modular abelian surfaces over $`\mathbf{Q}`$, with Michael Stoll, [arXiv:2312.07307](https://arxiv.org/abs/2312.07307), Forum of Mathematics, Sigma (2025)
  - Code: [strongBSDgenus2](https://github.com/TimoKellerMath/strongBSDgenus2) (Magma)

### Rational points on modular curves

- Explicit Coleman integration over finite extensions of $`\mathbf{Q}_p`$, with Yulin Cai, [arXiv:2610.33970](https://arxiv.org/abs/2610.33970)
  - Code: [ColemanIntegralsLocalFields](https://github.com/TimoKellerMath/ColemanIntegralsLocalFields) (Magma), including a Chabauty–Coleman solver over number fields
- Semi-stable models, local heights and quadratic Chabauty for $`X_0(N)^*`$, with Nikola Adžaga and Maarten Derickx, [arXiv:2609.40207](https://arxiv.org/abs/2609.40207)
  - Code: [nt-lib/local-heights-X0Nstar](https://github.com/nt-lib/local-heights-X0Nstar) (Magma)
- Rational points on $`X_0(N)^*`$ when $`N`$ is non-squarefree, with Sachi Hashimoto and Samuel Le Fourn, [arXiv:2505.00680](https://arxiv.org/abs/2505.00680)
  - Code: [sachihashimoto/X0Nstarquotients](https://github.com/sachihashimoto/X0Nstarquotients) (Magma, SageMath)
- Towards a classification of isolated $`j`$-invariants, with Abbey Bourdon, Sachi Hashimoto, Zev Klagsbrun, David Lowry-Duda, Travis Morrison, Filip Najman, and Himanshu Shukla, [arXiv:2311.07740](https://arxiv.org/abs/2311.07740), Mathematics of Computation (2025)
  - Code: [davidlowryduda/isolated_points](https://github.com/davidlowryduda/isolated_points) (Magma)
- Computing quadratic points on modular curves $`X_0(N)`$, with Nikola Adžaga, Philippe Michaud-Jacobs, Filip Najman, Ekin Ozman, and Borna Vukorepa, [arXiv:2303.12566](https://arxiv.org/abs/2303.12566), Mathematics of Computation (2024)
  - Code: [QuadraticPoints](https://github.com/TimoKellerMath/QuadraticPoints) (Magma)
- Quadratic Chabauty for Atkin–Lehner quotients of modular curves of prime level and genus 4, 5, 6, with Nikola Adžaga, Vishal Arul, Lea Beneish, Mingjie Chen, Shiva Chidambaram, and Boya Wen, [arXiv:2105.04811](https://arxiv.org/abs/2105.04811), Acta Arithmetica (2023)
  - Code: [AWS2020QC/ModularCurvesX0plusG4-6](https://github.com/AWS2020QC/ModularCurvesX0plusG4-6) (Magma)
- Rational points on hyperelliptic Atkin–Lehner quotients of modular curves and their coverings, with Nikola Adžaga, Shiva Chidambaram, and Oana Padurariu, [arXiv:2203.05541](https://arxiv.org/abs/2203.05541), Research in Number Theory (2022)
  - Code: [shiva-chid/Hyperelliptic_X0Nstarquotients](https://github.com/shiva-chid/Hyperelliptic_X0Nstarquotients) (Magma)

### Inverse Galois theory for 17T7

- 17T7 is a Galois group over the rationals, with Raymond van Bommel, Edgar Costa, Noam D. Elkies, Sam Schiavone, and John Voight, [arXiv:2411.07857](https://arxiv.org/abs/2411.07857), Algebra & Number Theory (to appear)
  - Code: [SamSchiavone/17T7](https://github.com/SamSchiavone/17T7) (Magma, SageMath, Julia) and [edgarcosta/EichlerShimuraHMF](https://github.com/edgarcosta/EichlerShimuraHMF) (Magma)

### Abelian varieties over finite fields and their zeta function

- Point counts of abelian varieties over finite fields determining their zeta function, with Shiva Chidambaram, [arXiv:2606.28989](https://arxiv.org/abs/2606.28989)
  - Code: [PointCountsAbelianVarieties](https://github.com/TimoKellerMath/PointCountsAbelianVarieties) (SageMath, Python, Lean 4)

### Étale fundamental groups of arithmetic surfaces

- Golod–Shafarevich for arithmetic surfaces, with Carlo Pagano, [arXiv:2610.06461](https://arxiv.org/abs/2610.06461)
  - Lean formalization: [GolodShafarevichFormalization](https://github.com/TimoKellerMath/GolodShafarevichFormalization) (Lean 4)

## Work in progress

- [SamSchiavone/ModularCurves](https://github.com/SamSchiavone/ModularCurves) (Magma, Python): code and data for the database of modular curves in the [LMFDB](https://www.lmfdb.org), from the modular curves workshops at MIT in [March 2022](https://math.mit.edu/~edgarc/MCW.html), [November 2022](https://math.mit.edu/~edgarc/MCW2.html), and [March 2024](https://math.mit.edu/~edgarc/MCW3.html)

## Other projects

- [quadratic-sieve](https://github.com/TimoKellerMath/quadratic-sieve) (Rust): factors integers with the self-initializing/multiple polynomial quadratic sieve (SIQS/MPQS)
- [ChoraleHarmonizer](https://github.com/TimoKellerMath/ChoraleHarmonizer) (Python, PyTorch, music21): takes a soprano melody and writes the alto, tenor, and bass in the style of Johann Sebastian Bach, with a small Transformer model and voice-leading rules
