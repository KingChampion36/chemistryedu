---
title: Thermodynamics | Enthalpy
description: Enthalpy is the heat content of a system at constant pressure.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Thermodynamics | Enthalpy

## Enthalpy (H)

* The heat content of a system at constant pressure is called enthalpy.
* Enthalpy of a system can be represented as a function of pressure, P and temperature, T.

!!! tip ""

    $$H = f(P,\ T)$$

    $$Partially\ differentiating\ both\ sides:$$

    $$dH = {({dH \over dP})}_T dP + {({dH \over dT})}_P dT$$

    $$Here, {({dH \over dP})}_T = Change\ in\ H\ w.r.t\ P\ at\ constant\ temperature$$

    $$Here, {({dH \over dT})}_P = Change\ in\ H\ w.r.t\ T\ at\ constant\ pressure$$

    $$Since,\ pressure\ is\ constant.\ So,\ dP = 0$$

    $$dH = {({dH \over dT})}_P dT$$

    $$For\ 1\ mole\ of\ ideal\ gas:$$

    $$dH = C_pdT$$

    $$For\ n\ moles\ of\ ideal\ gas:$$

    $$dH = nC_pdT$$

    $$Integrating\ both\ sides:$$

    $$ \int\limits_{H_1}^{H_2} dH = \int\limits_{T_1}^{T_2} nC_pdT$$

    $$H_2 - H_1 = \int\limits_{T_1}^{T_2} nC_pdT$$

    $$&Delta;H = \int\limits_{T_1}^{T_2} nC_pdT$$

    $$Here,\ C_p = Molar\ heat\ capacity\ at\ constant\ pressure$$

* If &Delta;H is negative, then heat is released and reaction is exothermic.
* If &Delta;H is positive, then heat is absorbed and reaction is endothermic.

## Relation between Internal Energy (U) and Enthalpy (H)

* The relation between U and H is given by the following equation:

!!! tip ""

    $$H = U + PV$$

    $$Differentiating\ both\ sides:$$

    $$dH = dU + d(PV)$$

* If pressure P is constant (isobaric process), we can write:

!!! tip ""

    $$dH = dU + d(PV)$$

    $$dH = dU + PdV$$

    $$Integrating\ both\ sides:$$

    $$\int\limits_{H_1}^{H_2} dH = \int\limits_{U_1}^{U_2} dU + P \int\limits_{V_1}^{V_2} dV$$

    $$H_2 - H_1 = (U_2 - U_1) + P(V_2 - V_1)$$

    $$&Delta;H = &Delta;U + P &Delta;V$$


* If Volume V is constant (isochoric process), we can write:

!!! tip ""

    $$dH = dU + d(PV)$$

    $$dH = dU + VdP$$

    $$Integrating\ both\ sides:$$

    $$\int\limits_{H_1}^{H_2} dH = \int\limits_{U_1}^{U_2} dU + V \int\limits_{P_1}^{P_2} dP$$

    $$H_2 - H_1 = (U_2 - U_1) + V(P_2 - P_1)$$

    $$&Delta;H = &Delta;U + V &Delta;P$$

* For a gaseous phase chemical reaction containing ideal gases:

!!! tip ""

    $$dH = dU + d(PV)$$

    $$dH = dU + d(nRT)$$

    Since, most chemical reactions occur at constant temperature:

    $$dH = dU + RT(dn)$$

    $$Integrating\ both\ sides:$$

    $$\int\limits_{H_1}^{H_2} dH = \int\limits_{U_1}^{U_2} dU + RT \int\limits_{n_1}^{n_2} dn$$

    $$H_2 - H_1 = (U_2 - U_1) + RT (n_2 - n_1)$$

    $$&Delta;H = &Delta;U + &Delta;n_g RT$$

    Here, &Delta;n<sub>g</sub> = Gaseous moles of products - Gaseous moles of reactants
