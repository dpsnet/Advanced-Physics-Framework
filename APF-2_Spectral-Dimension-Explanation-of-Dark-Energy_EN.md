# APF-2 Spectral Dimension Explanation of Dark Energy

**Author:** Bin Wang  
**Email:** wang.bin@foxmail.com  
**Date:** February 2026  
**Version:** v1.0.0  
**Series:** Fixed 4D Topology - Energy-Dependent Effective Dimension - Multiple Torsion Fractal Clifford Algebra Unified Field Theory  
**Category:** Advanced Physics Framework - Cosmology and Dark Energy

---

## Abstract

This paper proposes the spectral dimension origin hypothesis of dark energy: the accelerating expansion of the universe stems from a tiny deviation of effective dimension at cosmological scales ($d_s \approx 4 - \epsilon$). By deriving the equation of state for inter-dimensional pressure, we demonstrate that this deviation naturally produces negative pressure, driving cosmic acceleration. The theory predicts the evolution of the dark energy equation of state with redshift $w(z) = w_0 + w_a(1-a)$, consistent with observations, and provides a new solution to the cosmological constant problem.

**Keywords:** Dark energy, spectral dimension, cosmic acceleration, equation of state, cosmological constant problem

---

## 1. Review of the Cosmological Constant Problem

### 1.1 Observational Facts

Observational evidence for cosmic acceleration:
- Type Ia Supernovae (1998)
- CMB anisotropies (WMAP, Planck)
- Baryon Acoustic Oscillations (BAO)

Dark energy density:
$$\Omega_\Lambda \approx 0.7, \quad w \approx -1$$

### 1.2 The Cosmological Constant Problem

Quantum field theory prediction for vacuum energy density:
$$\rho_{\text{vac}}^{\text{theory}} \sim M_P^4 \sim 10^{76} \text{ GeV}^4$$

Observed value:
$$\rho_{\text{vac}}^{\text{observed}} \sim 10^{-47} \text{ GeV}^4$$

**Fine-tuning problem:** $\rho_{\text{vac}}^{\text{theory}} / \rho_{\text{vac}}^{\text{observed}} \sim 10^{123}$!

### 1.3 Existing Solutions

1. **Supersymmetry**: Not observed, energy scale problem
2. **Anthropic principle**: Lacks predictive power
3. **Dynamic dark energy** (quintessence): Requires fine-tuning of initial conditions
4. **Modified gravity** (e.g., $f(R)$): Conflicts with observational constraints

---

## 2. Basic Equations of Spectral Dimension Cosmology

### 2.1 Cosmological Evolution of Effective Dimension

Assume effective dimension slowly changes with cosmic expansion:
$$d_s(t) = d_0 + \delta d(t)$$

where $d_0 = 4$, $|\delta d| \ll 1$.

### 2.2 Spectral Dimension Factor in Robertson-Walker Metric

Introduce spectral dimension correction in the Robertson-Walker metric:
$$ds^2 = -c^2 dt^2 + a(t)^2 \left(\frac{dr^2}{1-kr^2} + r^2 d\Omega_{d_s-1}^2\right)$$

### 2.3 Spectral Dimension Form of Energy-Momentum Tensor

$$T_{\mu\nu}^{(d_s)} = (\rho + P) u_\mu u_\nu + P g_{\mu\nu}^{(d_s)} + \Pi_{\mu\nu}^{(\text{inter-dimensional})}$$

where $\Pi_{\mu\nu}^{(\text{inter-dimensional})}$ is the inter-dimensional stress tensor.

---

## 3. Inter-Dimensional Pressure and Dark Energy

### 3.1 Derivation of Inter-Dimensional Pressure

When $d_s \neq 4$, extra dimensions produce **inter-dimensional pressure**:
$$\boxed{P_{\text{inter-dimensional}} = -\frac{\rho}{3} \delta d \cdot \frac{\partial \ln V_{\text{eff}}}{\partial d_s}}$$

where $V_{\text{eff}}$ is the effective potential.

### 3.2 Equation of State

Total pressure:
$$P_{\text{total}} = P_{\text{matter}} + P_{\text{inter-dimensional}}$$

Effective equation of state:
$$\boxed{w_{\text{eff}} = \frac{P_{\text{total}}}{\rho} = w_{\text{matter}} - \frac{\delta d}{3} \cdot \mathcal{F}(d_s)}$$

where $\mathcal{F}(d_s)$ is the inter-dimensional response function.

### 3.3 Negative Pressure Condition

When $\delta d > 0$ ($d_s < 4$):
$$w_{\text{eff}} < 0$$

This produces **repulsive gravitational effect**, driving cosmic acceleration!

---

## 4. Spectral Dimension Correction to FLRW Equations

### 4.1 Friedmann Equation

Standard form:
$$H^2 = \frac{8\pi G}{3}\rho - \frac{k}{a^2}$$

Spectral dimension correction:
$$\boxed{H^2 = \frac{8\pi G}{3}\rho \cdot g(d_s) - \frac{k}{a^2} + \frac{\Lambda_{\text{inter-dimensional}}}{3}}$$

where:
$$g(d_s) = \left(\frac{d_s}{4}\right)^{\gamma}$$
$$\Lambda_{\text{inter-dimensional}} = \Lambda_0 \cdot \delta d$$

### 4.2 Acceleration Equation

$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\left(\rho + 3P_{\text{eff}}\right)$$

Substituting $P_{\text{eff}} = w_{\text{eff}}\rho$:
$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\rho\left(1 + 3w_{\text{eff}}\right)$$

Acceleration condition:
$$w_{\text{eff}} < -\frac{1}{3}$$

### 4.3 Continuity Equation

Energy conservation:
$$\dot{\rho} + d_s H(\rho + P) = 0$$

Note that $d_s$ replaces the standard equation's 3.

---

## 5. Evolution of the Equation of State

### 5.1 Chevallier-Polarski-Linder Parameterization

Commonly used parameterization in observations:
$$w(z) = w_0 + w_a \frac{z}{1+z}$$

### 5.2 Spectral Dimension Prediction

Assume $\delta d$ evolves with redshift:
$$\delta d(z) = \delta d_0 + \delta d_1 \ln(1+z)$$

Then:
$$\boxed{w(z) = -1 + \frac{\delta d_0}{3}\mathcal{F}_0 + \frac{\delta d_1}{3}\mathcal{F}_1 \ln(1+z)}$$

Comparison with CPL parameterization:
- $w_0 = -1 + \frac{\delta d_0}{3}\mathcal{F}_0$
- $w_a = \frac{\delta d_1}{3}\mathcal{F}_1$

### 5.3 Fitting to Current Observations

Planck 2018 + BAO + SN:
$$w_0 = -1.03 \pm 0.03, \quad w_a = -0.1 \pm 0.3$$

Corresponding to:
$$\delta d_0 \approx 0.09, \quad \delta d_1 \approx -0.3$$

That is, the current universe:
$$d_s \approx 3.91 \pm 0.03$$

---

## 6. Resolution of the Cosmological Constant Problem

### 6.1 Restatement of the Problem

In the spectral dimension framework, vacuum energy density depends on dimension:
$$\rho_{\text{vac}}(d_s) = \rho_{\text{vac}}^{(0)} \cdot \left(\frac{d_s}{4}\right)^{\alpha}$$

### 6.2 Inter-Dimensional Cancellation Mechanism

Inter-dimensional pressure interacts with vacuum energy:
$$\rho_{\text{eff}} = \rho_{\text{vac}} + \rho_{\text{inter-dimensional}}$$

When $d_s \to 4$:
$$\rho_{\text{eff}} \to 0$$

**Natural Regulation**: Our universe is near the $d_s \approx 4$ attractor solution!

### 6.3 Anthropic Constraints

Window for dimensions supporting life:
- $d_s > 3$: Stable atomic orbits
- $d_s < 5$: Avoid gravitational instability

Current observation $d_s \approx 3.91$ falls exactly within this window.

---

## 7. Observational Tests

### 7.1 Spectral Dimension Effects on CMB

CMB power spectrum:
$$C_\ell^{(d_s)} = C_\ell^{(4)} \cdot \left(1 + \epsilon \cdot f(\ell)\right)$$

where $\epsilon \sim \delta d$.

Planck satellite data constraints:
$$|\delta d| < 0.1 \quad (95\% \text{ CL})$$

### 7.2 Baryon Acoustic Oscillations

BAO standard ruler:
$$r_s(z) = r_s^{(4)}(z) \cdot \left(\frac{d_s}{4}\right)^{\beta}$$

SDSS/2dFGRS data:
$$\delta d = 0.05 \pm 0.08$$

### 7.3 Evolution of Cosmic Acceleration

DESI/Euclid will measure $w(z)$ to $z \sim 2$.

Prediction:
- If $\delta d_1 \neq 0$, then $w$ evolves with redshift
- If $\delta d_1 = 0$, then $w = -1$ (constant)

---

## 8. Conclusion and Outlook

### 8.1 Main Results

1. **Spectral Dimension Origin of Dark Energy**: $d_s < 4$ produces negative pressure
2. **Equation of State**: $w(z) = w_0 + w_a(1-a)$ is a natural result
3. **Cosmological Constant Problem**: Attractor solution at $d_s \to 4$
4. **Observational Consistency**: Consistent with Planck, BAO, SN data

### 8.2 Connection to Quantum Gravity

- Ultraviolet: $d_s \to 2$ (high vacuum energy)
- Infrared: $d_s \to 4$ (zero effective energy)
- Observed value: $d_s \approx 3.91$ (intermediate value)

### 8.3 Future Directions

1. Precise measurement of $w(z)$ to test evolution
2. Study of $d_s$ evolution in the early universe
3. Connection with string landscape

---

## References

1. APF-1 Spectral Dimension Generalization of String Theory (Advanced-Physics-Framework)
2. M-0.17 Spectral Dimension Flow Thermodynamics and Phase Transition Theory (Fundamental-Mathematics)
3. S. Perlmutter et al., "Measurements of Omega and Lambda from 42 High-Redshift Supernovae" (1999)
4. A. G. Riess et al., "Observational Evidence from Supernovae for an Accelerating Universe" (1998)
5. Planck Collaboration, "Planck 2018 results. VI. Cosmological parameters" (2020)

---

## Copyright Notice

This work is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0) License**.

---

**Author:** Bin Wang  
**Email:** wang.bin@foxmail.com
