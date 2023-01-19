---
title: Thermodynamics | Entropy
description: Entropy is defined as the degree of randomness or disorderness of a system. Entropy is an extensive property and a state function.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Thermodynamics | Entropy

## Entropy

* The measure of degree of randomness of a system is known as its entropy.
* Entropy is an extensive property. Thus, more is the number of molecules, more is the randomness or entropy.
* Entropy of gas is greater than that of liquid or solid. Similarly, entropy of liquid is greater than that of the solid.
* Entropy is a state function, ie, its value depends only on initial and final states.
* Mathematically, entropy (S) can be expressed as:

!!! tip ""

    $$dS = {dq_{rev} \over T}$$

    $$ \int dS = \int {dq_{rev} \over T}$$

    $$ &Delta;S = \int {dq_{rev} \over T}$$

    $$ &Delta;S = \int {nC_pdT \over T}$$

    Here, q<sub>rev</sub> = Heat exchanged by the system reversibly and T = temperature

* For a spontaneous process, change in entropy will be positive (&Delta;S > 0).
* Entropy of a system is maximum at equilibrium.
* Entropy gives the quantitative idea about the unavailable energy of a system, ie, the energy which cannot be used for performing useful work.

## Calculation of change in entropy for an ideal gas

!!! tip ""

    $$dS = {dq_{rev} \over T}$$

By first law of thermodynamics, dq<sub>rev</sub> = dU - W

!!! tip ""

    $$dS = {dU - dW \over T}$$

    $$dS = {dU - (-PdV) \over T}$$

    $$dS = {dU + PdV \over T}$$

Since, dU = nC<sub>v</sub>dT, we can write:

!!! tip ""

    $$dS = {nC_vdT + PdV \over T}$$

Integrating both sides:

!!! tip ""

    $$ \int\limits_{S_1}^{S_2}dS = \int\limits_{T_1}^{T_2}{nC_v \over T}dT + \int\limits_{V_1}^{V_2}{P \over T}dV$$

    $$ S_2 - S_1 = \int\limits_{T_1}^{T_2}{nC_v \over T}dT + \int\limits_{V_1}^{V_2}{nRT \over VT}dV$$

    $$&Delta;S = nC_v \int\limits_{T_1}^{T_2}{1 \over T}dT + nR \int\limits_{V_1}^{V_2}{1 \over V}dV$$

    $$ {&Delta;S = nC_vln{T_2 \over T_1} + nRln{V_2 \over V_1}}$$

Let's derive the formula for &Delta;S in terms of C<sub>p</sub>:

!!! tip ""

    $$&Delta;S = n(C_p-R)ln{T_2 \over T_1} + nRln{V_2 \over V_1}$$

    $$&Delta;S = nC_pln{T_2 \over T_1} - nRln{T_2 \over T_1} + nRln{V_2 \over V_1}$$

    $$&Delta;S = nC_pln{T_2 \over T_1} + nRln{V_2T_1 \over T_2V_1}$$

Since, P &Proportional; (T/V):

!!! tip ""

    $$ {&Delta;S = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}}$$

!!! info "Case 1. For an isochoric process"

    In an isochoric process, volume remains constant. So, V<sub>1</sub> = V<sub>2</sub>.

    $$&Delta;S = nC_vln{T_2 \over T_1} + nRln{V_2 \over V_1}$$

    $$&Delta;S = nC_vln{T_2 \over T_1}$$

!!! info "Case 2. For an isobaric process"

    In an isobaric process, pressure remains constant. So, P<sub>1</sub> = P<sub>2</sub>.

    $$&Delta;S = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}$$

    $$&Delta;S = nC_pln{T_2 \over T_1}$$

!!! info "Case 3. For an isothermal Process"

    In an isothermal process, temperature remains constant. So, T<sub>1</sub> = T<sub>2</sub>.

    $$&Delta;S = nC_vln{T_2 \over T_1} + nRln{V_2 \over V_1}$$

    $$&Delta;S = nRln{V_2 \over V_1}$$

    $$Or,\ &Delta;S = nRln{P_1 \over P_2}$$

!!! info "Case 4. When two gases are mixed at same temperature in a container"

    * Let us consider two gases A and B with moles n<sub>A</sub> and n<sub>B</sub> be mixed together in a container of volume V.

    * For gas A, let initial pressure, P<sub>1</sub> = (n<sub>A</sub>RT / V) and final pressure P<sub>2</sub> = ((n<sub>A</sub> + n<sub>B</sub>)RT / V)

    $$&Delta;S_A = n_ARln{P_1 \over P_2}$$

    $$&Delta;S_A = n_ARln{{n_ART \over V} \over {(n_A + n_B)RT \over V}}$$

    $$&Delta;S_A = n_ARln{n_A \over n_A + n_B}$$

    We know that n<sub>A</sub> / (n<sub>A</sub> + n<sub>B</sub>) = mole fraction of A (&Chi;<sub>A</sub>).

    $$&Delta;S_A = n_ARln&Chi;_A$$

    * Similarly for gas B, entropy change is given by:

    $$&Delta;S_B = n_BRln&Chi;_B$$

    * Total entropy change is given by:

    $$&Delta;S_{total} = &Delta;S_A + &Delta;S_B$$

    $$ {&Delta;S_{total} = n_ARln&Chi;_A + n_BRln&Chi;_B} $$

    * Total molar entropy (entropy per mole) is given by:

    $$&Delta;S_m = {n_A \over n_A + n_B}Rln&Chi;_A + {n_B \over n_A + n_B}Rln&Chi;_B$$

    $$ {&Delta;S_m = &Chi;_ARln&Chi;_A + &Chi;_BRln&Chi;_B} $$

## Change in entropy of system, surrounding and universe

* Let the change in entropy of universe be denoted by &Delta;S<sub>total</sub>.

!!! tip ""

    $$ &Delta;S_{total} = &Delta;S_{system} + &Delta;S_{surrounding} $$

!!! info "Case 1. For a reversible process"

    For a reversible process, total entropy change, &Delta;S<sub>total</sub> is zero.

    $$ &Delta;S_{total} = &Delta;S_{system} + &Delta;S_{surrounding} = 0 $$

    $$ &Delta;S_{system} = - &Delta;S_{surrounding} $$

!!! info "Case 2. For an irreversible process"

    * For an irreversible process, entropy change of surrounding (&Delta;S<sub>surrounding</sub>) is given by:

    $$&Delta;S_{surrounding} = {-q_{irr} \over T}$$

    where, q<sub>irr</sub> = heat absorbed by the surrounding during irreversible process

    * Total entropy change or entropy change of universe is given by:

    $$ &Delta;S_{total} = &Delta;S_{system} + &Delta;S_{surrounding} $$

    $$ &Delta;S_{total} = {{1 \over T} \int dq_{rev}} - {q_{irr} \over T} $$

    $$ &Delta;S_{total} = {q_{rev} \over T} - {q_{irr} \over T} $$

    * It is worth noting that all irreversible processes (or, natural processes) are spontaneous processes. So, &Delta;S<sub>total</sub> will always be positive.

    $$ &Delta;S_{total} > 0$$

    $$ {q_{rev} \over T} - {q_{irr} \over T} > 0$$

    $$ {q_{rev} \over T} > {q_{irr} \over T} $$

    $$ q_{rev} > q_{irr} $$

    * For an adiabatic irreversible process, q<sub>irr</sub> = 0 because surrounding does not exchange heat with the system. So, &Delta;S<sub>surrounding</sub> = 0.

    So, for an adiabatic irreversible process:

    $$&Delta;S_{total} = &Delta;S_{system}$$

!!! info "Case 3. For free expansion"

    * In free expansion, W = 0, q = 0 and &Delta;U = 0.

    * Surrounding exchange no heat with the system. So, q<sub>irr</sub> = 0. Therefore, &Delta;S<sub>surrounding</sub> = 0.

    * Total entropy change is given by:

    $$ &Delta;S_{total} = &Delta;S_{system} + &Delta;S_{surrounding} $$

    $$ S_{total} = &Delta;S_{system} $$

## Thermal Death of Universe

* All natural processes are irreversible and spontaneous. So, change in entropy of natural processes will always be greater than zero.
* In other words, the entropy of the universe is constantly increasing for irreversible processes.
* Entropy is constantly increasing, ie, unavailable energy is constantly increasing. This leads to the conclusion that a time will come when no energy will be available for doing work. This is known as thermal death of universe.
