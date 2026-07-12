# Raumvektortheorie (RVT) – Extended Vector-Tensor Gravity Framework

An alternative, fully covariant vector-tensor geometric theory extending General Relativity (GR) to explain cosmic dynamics, flat galaxy rotation curves, and lensing anomalies without the necessity of Dark Matter (DM) or Dark Energy (DE)[cite: 1, 2]. 

The Raumvektortheorie (RVT) breaks the traditional 180-degree location-invariance of gravitation by introducing a dynamic projection mechanics ($\mathbb{R}^3 \rightarrow \mathbb{R}^2$) onto a dynamic, relative Lorentzian Aether ($A_{Lor}$) via 90-degree and 270-degree space vector projections[cite: 2].

---

## 1. Theoretical Foundation & Action Principle

The RVT action extends General Relativity by introducing a scalar projection field $\Xi(x)$ (or vector field $n_\mu(x)$) that directly couples to spacetime curvature[cite: 1, 2].

### The Action
The total action is defined as:
$$S_{RVT}=\int d^{4}x\sqrt{-g}\left[\frac{R}{16\pi G}+\alpha\left(-\Xi R+\frac{\omega}{2\Xi}(\nabla\Xi)^{2}\right)+\mathcal{L}_{matter}\right]$$

Where:
* $R$ is the Ricci scalar[cite: 1].
* $g$ is the determinant of the metric tensor $g_{\mu\nu}$[cite: 1].
* $\Xi(x)$ is the scalar projection field[cite: 1].
* $\alpha$ and $\omega$ are coupling constants, where $\alpha$ scales with the universal coupling constant $C_{RVT}$[cite: 1].
* $\mathcal{L}_{matter}$ is the Lagrangian density for matter fields[cite: 1].

### Field Equations
Varying the action with respect to the metric $g_{\mu\nu}$ yields the modified field equations[cite: 1]:
$$G_{\mu\nu}+\alpha E_{\mu\nu}=8\pi GT_{\mu\nu}$$

The RVT correction tensor $E_{\mu\nu}$ is explicitly constructed via the scalar projection field[cite: 1, 2]:
$$E_{\mu\nu}=\nabla_{\mu}\nabla_{\nu}\Xi-g_{\mu\nu}\Box\Xi$$

Varying the action with respect to the projection field $\Xi$ produces its equation of motion[cite: 1]:
$$\Box\Xi+\frac{\omega}{\alpha}\left(\frac{(\nabla\Xi)^{2}}{2\Xi}-\frac{R}{6}\right)=0$$

---

## 2. Post-Newtonian Limit & Galactic Rotation Curves

In the weak-field limit ($g_{\mu\nu} = \eta_{\mu\nu} + h_{\mu\nu}$), the linearized field equations reduce to a modified Poisson equation[cite: 1, 2]:
$$\nabla^{2}\Phi=4\pi G\rho+\frac{\alpha}{\lambda r}$$

### Universal Coupling Constant $C_{RVT}$
Empirical fits to observational galactic data (e.g., the THINGS survey) yield a dimensionless, universal coupling constant[cite: 1, 2]:
$$C_{RVT} = \frac{\alpha}{\lambda} \approx 0.8 \pm 0.2$$

### Velocity Equation
The total rotational velocity of a galaxy is governed by[cite: 1]:
$$v_{total}^{2}(r)=v_{baryon}^{2}(r)+C_{RVT}\cdot v_{flat}^{2}$$

The RVT projection field generates a linear potential contribution $\Phi_{RVT} = -\frac{\alpha r}{2\lambda}$, establishing a constant non-Newtonian gravitational acceleration $a_{RVT} = \frac{C_{RVT}}{2}$ that forces rotation curves flat without requiring dark matter halos[cite: 2].

---

## 3. The 90°/270° Asymmetry & Observable Anisotropy

The 2D Lorentzian Aether acts as a mirror that breaks classical symmetry, treating top and underside projections as physically asymmetric[cite: 2].

* **Top View ($90^\circ$):** Gravitational lensing is amplified ($\gamma_{RVT} = 1.8 \cdot \gamma_{ART}$)[cite: 2].
* **Underside View ($270^\circ$):** Gravitational lensing is suppressed ($\gamma_{RVT} = 0.2 \cdot \gamma_{ART}$)[cite: 2].

### Experimental Signature: Edge-on vs. Face-on Lensing
RVT predicts a distinct, falsifiable geometric anisotropy based on galactic inclination $i$[cite: 2]:
$$\gamma_{RVT} = \gamma_{ART} \cdot (1 + C_{RVT} \cdot \sin(i))$$

| Galaxy | Inclination ($i$) | RVT Boost | Projection Divergence ($D_{norm}$) | Observed $V_{obs}$ |
| :--- | :--- | :--- | :--- | :--- |
| **NGC 891** (Edge-on) | $85^\circ$ | $1.797\times$ | $0.998$ | $222\text{ km/s}$[cite: 2] |
| **NGC 7331** (Interm.) | $76^\circ$ | $1.776\times$ | $0.985$ | $245-262\text{ km/s}$[cite: 2] |
| **M101** (Face-on) | $18^\circ$ | $1.247\times$ | $0.654$ | $25\text{ km/s}$[cite: 2] |

Statistical validation using two-sample Kolmogorov-Smirnov and Levene tests confirms that Edge-on galaxies display significantly broader, left-skewed velocity residuals ($\gamma_1 = -0.813$) due to the $270^\circ$ projection asymmetry[cite: 2].

---

## 4. Noether Theorem & Negentropy Energy Redistribution

Applying the Noether theorem under time-dependent projection fields ($\dot{\Xi} \neq 0$) uncovers a unique cosmological mechanism: the redistribution of energy between 3D spacetime and the 2D Aether plane[cite: 3].

### Hamilton Density & Continuity Equation
$$\mathcal{H}=\frac{1}{2}\dot{\vec{R}}^{2}+V(\vec{R},\Xi)+\alpha(\nabla\Xi)^{2}$$

In dynamic scenarios, the localized energy conservation equation yields[cite: 3]:
$$\frac{\partial\mathcal{H}}{\partial t}+\nabla\cdot\vec{J}_{E}=-\frac{\partial\mathcal{H}_{proj}}{\partial t}$$

Where $\mathcal{H}_{proj}$ represents the energy density mapped onto the 2D Aether[cite: 3]. Total global energy is conserved ($\mathcal{H} + \mathcal{H}_{proj} = \text{const}$)[cite: 3]. Negentropy emerges from the Folding Sphere (USK) structural compression, optimizing internal layer order ($n \rightarrow \infty \implies \vec{S} \rightarrow 0$)[cite: 2, 3].

### Verification & Experimental Testing
1. **Clock Comparison:** Atomic clocks (e.g., Caesium vs. Rubidium) will exhibit tiny synchronization variances in highly dynamic gravitational environments (e.g., near pulsars) when $\dot{\Xi} \neq 0$[cite: 3].
2. **Cosmological Redshift:** Measurable deviations from the classical Hubble relation due to active geometric projection drift ($dA_{Lor}/dt$)[cite: 2, 3].
