# Vector Spaces, Linear Transformations, and LU Factorization in Infectious Disease Modeling
**[Read the paper (PDF)](https://github.com/charlenejamiemiciano/tb-ngm-linear-algebra/blob/main/ngm_final.pdf)**
An applied linear algebra paper connecting core concepts (vector spaces, linear
transformations, LU factorization) to the next-generation matrix (NGM) method — the
standard technique for computing the basic reproduction number (R0) in structured
disease models, which I use in my own tuberculosis modeling work.

**Context:** Written for EN609 (Johns Hopkins Whiting School of Engineering, MS in
Applied and Computational Mathematics), June 2026.

**What it covers:**
- Deriving the NGM framework (K = FV⁻¹) from first principles
- How LU factorization and forward substitution solve the matrix inversion at the
  core of computing R0
- Applying the framework to compartmental disease models (SIR/SEIR and TB-specific
  cascade-of-care structures)

**Files:**
- `ngm_final.tex` — paper source
- `ngm_final.pdf` — compiled paper
