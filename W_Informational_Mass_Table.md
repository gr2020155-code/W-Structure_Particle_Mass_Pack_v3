# W-Informational Mass Table (v3)

Fundamental relation:

\[
m = \frac{1}{N}, \qquad N = 2 p q , \quad \gcd(p,q)=1
\]

All masses here are **informational**.  
Physical MeV/GeV masses appear only after projection using the electron as a single anchor.

---

## Core fermion set

| Particle | (p, q, s) | N = 2·p·q (order) | Notes |
|---|---|---|---|
| e | (109298261777, 109298261796, 1) | ~2.39×10²² | reference baseline |
| μ | (7601109838, 7600909837, 1) | ~1.16×10²⁰ | exact rational μ/e |
| τ | (1853576874, 1853458199, 1) | ~6.89×10¹⁸ | heavy lepton |
| u | (52800000003, 52800000001, 1) | ~5.57×10²¹ | light up-type quark |
| d | (36200000000, 36200000001, 1) | ~2.62×10²¹ | m_d/m_u is exact |
| s | (8094566078, 8094566079, 1) | ~1.31×10²⁰ | strange quark slot (predicted & matched) |
| c | (2210895679, 2210895680, 1) | ~9.78×10¹⁸ | charm quark slot |
| b | (1240000001, 1240000002, 1) | ~3.08×10¹⁸ | bottom quark slot |
| t | (188117481, 188117482, 1) | ~7.08×10¹⁶ | optimized top-quark slot |

---

## Exact mass ratios (informational)

For any two states A,B with N_A, N_B:

\[
\frac{m_A}{m_B} = \frac{N_B}{N_A}
\]

Examples (defined exactly by integers):

- \(\displaystyle \frac{m_\mu}{m_e} = \frac{N_e}{N_\mu}\)
- \(\displaystyle \frac{m_\tau}{m_\mu} = \frac{N_\mu}{N_\tau}\)
- \(\displaystyle \frac{m_d}{m_u} = \frac{N_u}{N_d}\)
- \(\displaystyle \frac{m_c}{m_s} = \frac{N_s}{N_c}\)

No floating parameters, no fits —  
only integer triples \((p,q,s)\) and the derived N.

---

## Projection note

To compare with experiment, one can choose the electron mass \(m_e\) as a single physical input and compute:

\[
m_{\text{phys}}(X) = m_e \cdot \frac{N_e}{N_X}
\]

All experimental uncertainties live **in this projection step**,  
not in the informational mass table itself.
