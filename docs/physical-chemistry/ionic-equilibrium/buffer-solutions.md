---
title: Ionic Equilibrium | Buffer Solutions
description: The solutions which resist change in pH on dilution or with the addition of small amounts of acid or alkali are called buffer solutions.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Ionic Equilibrium | Buffer Solutions

## Buffer Solutions

The solutions which resist change in pH on dilution or with the addition of small amounts of acid or alkali are called buffer solutions.

* Many body fluids like blood and urine have a definite pH, and any deviation indicates malfunctioning of the body. Control of pH is also important in many chemical and biochemical processes, and in medical and cosmetic formulations.
* A buffer of known pH can be prepared from the pK<sub>a</sub> of an acid (or pK<sub>b</sub> of a base) by controlling the ratio of salt and acid (or salt and base).

## Types of Buffer Solutions

### 1. Acidic buffer

* A mixture of a weak acid and its salt with a strong base.
* Example: Acetic acid and sodium acetate (CH<sub>3</sub>COOH + CH<sub>3</sub>COONa) acts as a buffer around pH 4.75.

### 2. Basic buffer

* A mixture of a weak base and its salt with a strong acid.
* Example: Ammonium hydroxide and ammonium chloride (NH<sub>4</sub>OH + NH<sub>4</sub>Cl) acts as a buffer around pH 9.25.

## Buffer Action

* A buffer contains a large reserve of both an acid (to consume added OH<sup>-</sup>) and a base (to consume added H<sup>+</sup>). The common ion effect keeps the weak electrolyte almost unionized.

!!! example "Acidic buffer: CH<sub>3</sub>COOH + CH<sub>3</sub>COONa"

    $$CH_3COONa &rarr; CH_3COO^- + Na^+\ (complete)$$

    $$CH_3COOH &#8652; CH_3COO^- + H^+\ (suppressed\ by\ common\ ion)$$

    * On adding a small amount of acid, the added H<sup>+</sup> combine with the large reserve of acetate ions:

    $$CH_3COO^- + H^+ &rarr; CH_3COOH$$

    * On adding a small amount of base, the added OH<sup>-</sup> are neutralized by acetic acid:

    $$CH_3COOH + OH^- &rarr; CH_3COO^- + H_2O$$

!!! example "Basic buffer: NH<sub>4</sub>OH + NH<sub>4</sub>Cl"

    * Added H<sup>+</sup> are consumed by NH<sub>4</sub>OH:

    $$NH_4OH + H^+ &rarr; NH_4^+ + H_2O$$

    * Added OH<sup>-</sup> are consumed by NH<sub>4</sub><sup>+</sup>:

    $$NH_4^+ + OH^- &rarr; NH_4OH$$

* In each case, only the ratio [salt]/[acid] changes slightly, so the pH changes very little.

## Henderson-Hasselbalch Equation

### 1. For an acidic buffer

* For a weak acid HA in presence of its salt:

!!! tip ""

    $$HA &#8652; H^+ + A^-,\ \ K_a = {[H^+][A^-] \over [HA]}$$

    $$[H^+] = K_a {[HA] \over [A^-]}$$

    Taking negative log on both sides:

    $$-log[H^+] = -log\ K_a - log{[HA] \over [A^-]}$$

    $$pH = pK_a + log{[A^-] \over [HA]}$$

* Since the acid is weakly ionized (and further suppressed by the common ion), [HA] &asymp; initial concentration of acid, and [A<sup>-</sup>] &asymp; concentration of salt.

!!! tip ""

    $$pH = pK_a + log{[Salt] \over [Acid]}$$

### 2. For a basic buffer

!!! tip ""

    $$BOH &#8652; B^+ + OH^-,\ \ K_b = {[B^+][OH^-] \over [BOH]}$$

    $$pOH = pK_b + log{[Salt] \over [Base]}$$

    $$pH = 14 - pOH = 14 - pK_b - log{[Salt] \over [Base]}$$

!!! tip "Conclusion"

    * The pH of a buffer depends on the ratio [salt]/[acid] (or [salt]/[base]), not on the actual amounts. Since dilution does not change this ratio, the pH of a buffer does not change on dilution.

    * When [salt] = [acid], pH = pK<sub>a</sub>. When [salt] = [base], pOH = pK<sub>b</sub>. The buffer resists change best (maximum buffer capacity) at this point.

    * A buffer works effectively in the range pH = pK<sub>a</sub> &plusmn; 1 (i.e., [salt]/[acid] between 1/10 and 10). So, to prepare a buffer of a desired pH, choose a weak acid whose pK<sub>a</sub> is close to that pH.

    * Since the Henderson equation uses concentrations in a ratio, moles (or millimoles) can be used directly when acid and salt are in the same solution.

## Questions

!!! question "Calculate the pH of solution formed on mixing 0.2 M NH<sub>4</sub>Cl and 0.1 M NH<sub>3</sub>. The pOH of ammonia solution is 4.75."

    The pOH value given here is used as pK<sub>b</sub> of ammonia:

    $$K_b = antilog(-pK_b) = 10^{-4.75} = 1.77 \times 10^{-5}$$

    $$NH_3 + H_2O &#8652; NH_4^+ + OH^-$$

    $$Equilibrium\ (M):\ \ 0.10 - x\ \ \ \ \ \ 0.20 + x\ \ \ \ \ \ x$$

    $$K_b = {(0.20 + x)(x) \over 0.10 - x} = 1.77 \times 10^{-5}$$

    As K<sub>b</sub> is small, x can be neglected compared to 0.1 M and 0.2 M:

    $$[OH^-] = x = 1.77 \times 10^{-5} \times {0.10 \over 0.20} = 0.88 \times 10^{-5}\ M$$

    $$[H^+] = {10^{-14} \over 0.88 \times 10^{-5}} = 1.12 \times 10^{-9}\ M$$

    $$pH = -log(1.12 \times 10^{-9}) = 8.95$$

    Using the Henderson equation directly:

    $$pOH = 4.75 + log{0.2 \over 0.1} = 4.75 + 0.30 = 5.05,\ \ pH = 8.95$$

!!! question "Calculate the pH of a buffer containing 0.1 M acetic acid and 0.2 M sodium acetate. (pK<sub>a</sub> of acetic acid = 4.74)"

    $$pH = pK_a + log{[Salt] \over [Acid]}$$

    $$pH = 4.74 + log{0.2 \over 0.1} = 4.74 + 0.30 = 5.04$$

!!! question "In what ratio should sodium acetate and acetic acid be mixed to obtain a buffer of pH 5.74? (pK<sub>a</sub> of acetic acid = 4.74)"

    $$5.74 = 4.74 + log{[Salt] \over [Acid]}$$

    $$log{[Salt] \over [Acid]} = 1$$

    $${[Salt] \over [Acid]} = 10$$

    So sodium acetate and acetic acid must be mixed in a 10 : 1 molar ratio.

!!! question "1 litre of a buffer contains 0.1 mol acetic acid and 0.1 mol sodium acetate (pK<sub>a</sub> = 4.74). Calculate the change in pH on adding (a) 0.01 mol HCl (b) 0.01 mol NaOH. Compare with the change when 0.01 mol HCl is added to 1 litre of pure water."

    Initial pH:

    $$pH = 4.74 + log{0.1 \over 0.1} = 4.74$$

    (a) Added H<sup>+</sup> converts acetate into acetic acid:

    $$CH_3COO^- + H^+ &rarr; CH_3COOH$$

    $$Acetate = 0.1 - 0.01 = 0.09\ mol,\ \ Acid = 0.1 + 0.01 = 0.11\ mol$$

    $$pH = 4.74 + log{0.09 \over 0.11} = 4.74 - 0.09 = 4.65$$

    (b) Added OH<sup>-</sup> converts acetic acid into acetate:

    $$Acetate = 0.11\ mol,\ \ Acid = 0.09\ mol$$

    $$pH = 4.74 + log{0.11 \over 0.09} = 4.74 + 0.09 = 4.83$$

    The pH changes by only about 0.09 unit. In pure water, 0.01 mol HCl in 1 litre gives [H<sup>+</sup>] = 0.01 M, so the pH falls from 7 to 2, a change of 5 units.

!!! question "50 mL of 0.2 M acetic acid is mixed with 50 mL of 0.1 M NaOH. Calculate the pH of the resulting solution. (pK<sub>a</sub> = 4.74)"

    $$mmol\ CH_3COOH = 0.2 \times 50 = 10,\ \ mmol\ NaOH = 0.1 \times 50 = 5$$

    $$CH_3COOH + NaOH &rarr; CH_3COONa + H_2O$$

    $$After\ reaction:\ \ CH_3COOH = 5\ mmol,\ \ CH_3COONa = 5\ mmol$$

    The solution is a buffer with equal amounts of acid and salt:

    $$pH = 4.74 + log{5 \over 5} = 4.74$$

    This is why the pH at half-neutralization of a weak acid equals its pK<sub>a</sub>.

!!! question "How many grams of NH<sub>4</sub>Cl must be added to 500 mL of 0.1 M NH<sub>3</sub> solution to obtain a buffer of pH 9.0? (pK<sub>b</sub> of NH<sub>3</sub> = 4.75, assume no change in volume)"

    $$pOH = 14 - 9.0 = 5.0$$

    $$5.0 = 4.75 + log{[NH_4Cl] \over [NH_3]}$$

    $${[NH_4Cl] \over [NH_3]} = 10^{0.25} = 1.78$$

    $$[NH_4Cl] = 1.78 \times 0.1 = 0.178\ M$$

    $$Moles\ of\ NH_4Cl = 0.178 \times 0.5 = 0.089\ mol$$

    $$Mass\ of\ NH_4Cl = 0.089 \times 53.5 = 4.76\ g$$
