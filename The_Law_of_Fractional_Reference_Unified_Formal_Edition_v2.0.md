# The Law of Fractional Reference — Unified Formal Edition (v2.0)
**Author:** Prajna Nanda (邱进德)  
**Date:** 2025-10-04  
**Version:** 2.0 (Unified Formal Edition)  
**License:** CC BY-NC-SA 4.0  

---

## **Abstract**
The **Law of Fractional Reference** establishes that proportional transformations (fractions, ratios, or scaling) create *new, self-consistent reference frames* rather than destroying the original whole.  
Each instance formed by such transformation retains internal structure but redefines its scale of completeness.  
This unified edition combines the conceptual, invariant, and formal mathematical aspects of the law into a single symbolic framework.

---

## **1. Foundations**

Let an initial *instance* \(I_0\) represent a complete system or "whole."  
A **fractional transformation** \(f_k \in \mathbb{R}_{>0}\) acts on a prior instance \(I_{k-1}\) to produce a new instance \(I_k\):

\[
I_k = f_k \, I_{k-1}.
\]

Repeated transformations produce:

\[
I_n = \Big(\prod_{k=1}^n f_k\Big) I_0.
\]

Each \(I_n\) constitutes a *new reference frame* with its own local "1" — a complete but scaled version of the original world.

---

## **2. Reference Operator and Normalization**

Define the **structure (or reference) operator**:

\[
\mathcal{R}(I) := \frac{I}{S(I)}, \quad S(I) = \sum_i x_i,
\]

where \(I = (x_1, x_2, \dots, x_m)\) represents measurable components of a system.  
\(\mathcal{R}(I)\) maps an instance to its *internal proportions* — its shape independent of size.

---

## **3. The Law of Fractional Reference (Formal Statement)**

> **For any instance** \(I \in \mathbb{R}^m_{>0}\) **and any positive scalar** \(f > 0\),  
> the normalized structure \(\mathcal{R}(I)\) remains invariant under uniform scaling:

\[
\mathcal{R}(f I) = \mathcal{R}(I).
\]

Hence, for any sequence of proportional transformations \(f_1, \dots, f_n\),

\[
\mathcal{R}(I_n) = \mathcal{R}(I_0).
\]

**Interpretation:** every fractional operation creates a new self-consistent universe whose internal laws are preserved though its scale changes.

---

## **4. Proof**

Let \(I = (x_1, \dots, x_m)\). Then \(fI = (f x_1, \dots, f x_m)\).  
Compute normalization:

\[
\mathcal{R}(fI) = \frac{fI}{S(fI)} = \frac{(f x_1, \dots, f x_m)}{f \sum_i x_i} = \frac{(x_1, \dots, x_m)}{\sum_i x_i} = \mathcal{R}(I).
\]

Therefore, \(\mathcal{R}\) is invariant under uniform scaling.  
□

---

## **5. Invariant Quantities**

### (a) Structural Invariant
\[
\mathcal{R}(I_n) = \mathcal{R}(I_0)
\]
indicates internal proportion remains unchanged across all reference frames.

### (b) Scale Delta
\[
M_n := \log\!\Big(\prod_{k=1}^{n} f_k\Big) = \sum_{k=1}^{n} \log f_k.
\]
This is the **additive distance in log-scale** — the objective measure of total scaling between frames.

### (c) Perceptual Delta
\[
P_n := d(\mathcal{R}(I_n), \mathcal{R}(I_{n-1})) = 0,
\]
for any pure scalar \(f_n\).  
This formalizes the “–1 feeling” — the momentary reset of perception despite structural constancy.

---

## **6. Transformation Space and Group Properties**

Let \(T_f: I \mapsto fI\) be the scaling operator.  
Then the collection \(\{T_f \mid f > 0\}\) forms an **abelian group** under composition:

\[
T_{f_2} \circ T_{f_1} = T_{f_2 f_1}, \quad T_1 = \text{id}.
\]

The inverse transformation restores reference:

\[
T_f^{-1} = T_{f^{-1}}.
\]

Hence, all fractional transformations belong to the multiplicative group \((\mathbb{R}_{>0}, \cdot)\), which preserves structure under normalization.

---

## **7. Perceptual Frame Reset (–1 Phenomenon)**

Each instance \(I_n\) defines its own **reference functional** \(\rho_n\) such that:

\[
\rho_n(I_n) = 1.
\]

For an observer bound to the previous frame \(\rho_{n-1}\), the same instance appears scaled by the accumulated product:

\[
\rho_{n-1}(I_n) = \prod_{k=1}^{n} f_k.
\]

The **perceptual difference** between frames is:

\[
\Delta \rho_n = \rho_n - \rho_{n-1},
\]

representing the re-anchoring of what is “whole.”  
Thus, every scaling introduces a discontinuity in perception but not in structure.

---

## **8. Conceptual Implications**

| Domain | Implication |
|---------|--------------|
| **Mathematics** | Offers a structural definition of invariance under proportional transformation. |
| **Physics** | Parallels Einsteinian relativity — laws remain invariant though reference frames change. |
| **AI / Computation** | Mirrors normalization layers in neural networks; each layer rescales data while preserving relational information. |
| **Cognitive Science** | Models how perception resets under context change without altering internal truth. |
| **Philosophy** | Bridges being and measurement: the world remains identical-in-structure though our scale of seeing shifts. |

---

## **9. Unified Summary**

\[
\boxed{
\begin{aligned}
I_n &= \Big(\prod_{k=1}^{n} f_k\Big) I_0, \\[6pt]
\mathcal{R}(I_n) &= \mathcal{R}(I_0), \\[6pt]
\rho_n(I_n) &= 1, \\[6pt]
\rho_{n-1}(I_n) &= \prod_{k=1}^{n} f_k.
\end{aligned}
}
\]

Each transformation preserves internal law (\(\mathcal{R}\)) while redefining external reference (\(\rho\)).  
This dual invariance—**structural constancy and perceptual reset**—constitutes the essence of the Law of Fractional Reference.

---

## **10. Concluding Note**

> The Law of Fractional Reference articulates the bridge between arithmetic scaling and frame-dependent perception.  
> It unites multiplicative recursion, structural invariance, and observer relativity into a single symbolic system.  
> The law stands as a demonstration that even within basic fractionality lies a universal principle of transformation.

---

## **Citation**

> Nanda, P. (2025). *The Law of Fractional Reference — Unified Formal Edition (v2.0).*  
> GitHub Repository: `prajna-nanda/Law_of_Fractional_Reference`  
> DOI pending / Timestamped via GitHub commit SHA.
