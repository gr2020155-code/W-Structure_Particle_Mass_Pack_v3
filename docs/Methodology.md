# Methodology — Generating Particles from Informational Lattice

The W-structure models fermion masses not as continuous values,
but as **discrete informational states** defined by integers:

\[
m_{\text{inf}} = \frac{1}{N}, \qquad N = 2^s \, p \, q,\quad \gcd(p,q)=1
\]

- \((p,q)\) are coprime integers
- \(s\) is a spin/information depth index (here s=1 for fermions)
- Physical mass projection uses the electron as the only reference

---

## Algorithm — How to generate any particle

1. **Select interval in N-space**
   - between known masses or beyond boundaries (heavy/light sectors)

2. **Pick target \(N_{target}\)**
   - **Nearest-slot method (B-type):** minimal \(|ΔN|\) → *mandatory neighbour*
   - **Geometric-mid method (A-type):** \(\sqrt{N_1 N_2}\) → *structured state*
   - Full approach (C) = B-first, A-optional

3. **Reconstruct \((p,q)\)**
   - solve \(N_{target}/2^s ≈ p·q\)
   - choose nearest consecutive integers \(p=n, q=n+1\)
   - ensure \(\gcd(p,q)=1\)

4. **Classify the state**
   - compare with known families by N-order
   - quark, lepton, neighbour, mid-state, heavy ladder, light mirror…

5. **Mass relations**
\[
\frac{m_X}{m_Y} = \frac{N_Y}{N_X}
\]
   Exact rational. No approximations.

6. **Projection to GeV (optional)**
\[
m_{phys}(X) = m_e \cdot \frac{N_e}{N_X}
\]
   Projection is where uncertainties enter — not in W itself.

---

## Remarks

- Known fermions form a sparse lattice occupation.
- **Empty lattice nodes = future particles.**
- The model is parameter-free, predictive, and scalable to new states.

See `docs/Roadmap_Detailed.md` for structural particle landscape.
