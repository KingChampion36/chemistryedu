---
title: Thermodynamics | Questions based on Entropy
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Thermodynamics | Questions based on Entropy

## Questions

??? question "For an ideal gas C<sub>p</sub> = 2.5R, calculate the change in entropy when 3 moles of this gas is heated from 300 K to 600 K at: (a) Constant pressure (b) Constant volume."

    $$Given\ values: n = 3,\ C_p = 2.5R,\ T_1 = 300\ K,\ T_2 = 600\ K$$
    
    $$C_v = C_p - R = 2.5R - R = 1.5R$$
    
    (a) Change in entropy at constant pressure:
    
    $$&Delta;S = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}$$
    
    $$&Delta;S = nC_pln{T_2 \over T_1}$$
    
    $$&Delta;S = 3 \times 2.5R \times ln{600 \over 300}$$
    
    $$&Delta;S = 7.5 \times 8.314 \times ln2$$
    
    $$&Delta;S = 43.22\ JK^{-1}$$
    
    (b) Change in entropy at constant volume:
    
    $$&Delta;S = nC_vln{T_2 \over T_1} + nRln{V_2 \over V_1}$$
    
    $$&Delta;S = nC_vln{T_2 \over T_1}$$
    
    $$&Delta;S = 3 \times 1.5R \times ln{600 \over 300}$$
    
    $$&Delta;S = 4.5 \times 8.314 \times ln2$$
    
    $$&Delta;S = 25.93\ JK^{-1}$$

??? question "Calculate the change in entropy when 3 moles of an ideal gas is heated and compressed simultaneously from 300 K, 1 atm to 400 K, 5 atm. (C<sub>p</sub> = 7R/2)"

    Applying the formula of &Delta;S:
    
    $$&Delta;S = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}$$
    
    $$&Delta;S = 3 \times {7R \over 2} ln{400 \over 300} + 3 \times R ln{1 \over 5}$$
    
    $$&Delta;S = 3 \times 3.5 \times 8.314 \times ln{4 \over 3} + 3 \times 8.314 \times ln{1 \over 5}$$
    
    $$&Delta;S = -15.03\ JK^{-1}$$
    
    Since, &Delta;S is negative, this process is non-spontaneous.

??? question "By how much does the entropy of 3 moles of an ideal gas change if pressure is reduced from 2 bar to 1 bar without any change in temperature?"

    $$&Delta;S = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}$$
    
    Since, temperature is constant, we can write:
    
    $$&Delta;S = nRln{P_1 \over P_2}$$
    
    $$&Delta;S = 3 \times 8.314 \times ln{2 \over 1}$$
    
    $$&Delta;S = 17.288\ JK^{-1}$$

??? question "Evaluate the change in entropy when 3 moles of an ideal gas is heated from 27<sup>o</sup>C to 727<sup>o</sup>C at constant pressure of 1 atm. (C<sub>p</sub> = 23.7 J K<sup>-1</sup>mol<sup>-1</sup>)"

    $$Given:\ T_1 = (27 + 273) = 300\ K$$
    
    $$and,\ T_2 = (727 + 273) = 1000\ K$$
    
    $$&Delta;S = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}$$
    
    Since, pressure is constant, we can write:
    
    $$&Delta;S = nC_pln{T_2 \over T_1}$$
    
    $$&Delta;S = 3 \times 23.7 \times ln{1000 \over 300}$$
    
    $$&Delta;S = 85.6\ JK^{-1}$$

??? question "Nitrogen is heated from 300 K to 600 K at constant pressure of 1 atm. Calculate the change in molar entropy if C<sub>p</sub> = 20 + 10 T, where T = temperature."

    $$&Delta;S = \int {dq_{rev} \over T}$$
    
    $$&Delta;S = \int\limits_{T_1}^{T_2} {nC_pdT \over T}$$
    
    Molar change in entropy means change in entropy per mole. So, molar entropy change &Delta;S_m is given by:
    
    $$&Delta;S_m = {&Delta;S \over n}$$
    
    $$&Delta;S_m = \int\limits_{T_1}^{T_2} {C_pdT \over T}$$
    
    $$&Delta;S_m = \int\limits_{T_1}^{T_2} {20 + 10T \over T}dT$$
    
    $$&Delta;S_m = \int\limits_{T_1}^{T_2} {20 \over T}dT + \int\limits_{T_1}^{T_2} {10T \over T}dT$$
    
    $$&Delta;S_m = 20 ln{T_2 \over T_1} + 10(T_2 - T_1)$$
    
    $$&Delta;S_m = 20 ln{600 \over 300} + 10(600 - 300)$$
    
    $$&Delta;S_m = 20 ln2 + 10 \times 300$$
    
    $$&Delta;S_m = 3013.863\ JK^{-1}mol^{-1}$$

??? question "A five litre container is divided so that 1 L of O<sub>2</sub> gas at 1 atm and 4 L of N<sub>2</sub> gas at 2 atm are on the two sides of the thin membrane. The membrane is then broken, allowing the gas to mix up at 300 K. Calculate the entropy of mixing for this process."

    * Moles of O<sub>2</sub> gas is given by:
    
    $$n_{O_2} = {PV \over RT}$$
    
    $$n_{O_2} = {1 \times 1 \over 0.0821 \times 300} = 0.0406$$
    
    * Moles of N<sub>2</sub> gas is given by:
    
    $$n_{N_2} = {PV \over RT}$$
    
    $$n_{N_2} = {2 \times 4 \over 0.0821 \times 300} = 0.3248$$
    
    * When two gases are mixed, mole fractions of O<sub>2</sub> and N<sub>2</sub> are:
    
    $$&Chi;_{O_2} = {n_{O_2} \over n_{O_2} + n_{N_2}}$$
    
    $$&Chi;_{O_2} = {0.0406 \over 0.0406 + 0.3248} = 0.11$$
    
    $$&Chi;_{N_2} = {n_{N_2} \over n_{O_2} + n_{N_2}} = 0.89$$
    
    * Entropy change for O<sub>2</sub>:
    
    $$&Delta;S_{O_2} = n_{O_2}Rln&Chi;_{O_2}$$
    
    $$&Delta;S_{O_2} = 0.0406 \times 8.314 \times ln(0.11) = -0.745\ JK^{-1}$$
    
    * Entropy change for N<sub>2</sub>:
    
    $$&Delta;S_{N_2} = n_{N_2}Rln&Chi;_{N_2}$$
    
    $$&Delta;S_{N_2} = 0.3248 \times 8.314 \times ln(0.89) = -0.315\ JK^{-1}$$
    
    * Total entropy change or entropy of mixing is given by:
    
    $$&Delta;S = &Delta;S_{O_2} + &Delta;S_{N_2}$$
    
    $$&Delta;S = (-0.745) + (-0.315) = -1.06\ JK^{-1}$$

??? question "Derive the condition to obtain maximum molar entropy change if two gases are mixed to form a binary mixture."

    * Let the two gases be denoted by A and B. Let the mole fraction of A = &Chi;<sub>A</sub> and mole fraction of B = 1 - &Chi;<sub>A</sub>. Molar entropy change of mixing of these two gases:
    
    $$&Delta;S_m = &Chi;_Aln&Chi;_A + (1 - &Chi;_A) ln (1 - &Chi;_A)$$
    
    $$&Delta;S_m = &Chi;_Aln&Chi;_A + ln (1 - &Chi;_A) - &Chi;_A ln (1 - &Chi;_A)$$
    
    * Differentiating with respect to &chi;<sub>A</sub>:
    
    $$ {d(&Delta;S_m) \over d&Chi;_A} = ln {&Chi;_A \over (1 - &Chi;_A)} $$
    
    * For maximum value of &Delta;S<sub>m</sub>:
    
    $$ {d(&Delta;S_m) \over d&Chi;_A} = 0 $$
    
    $$ ln {&Chi;_A \over (1 - &Chi;_A)} = 0 $$
    
    $$ {&Chi;_A \over (1 - &Chi;_A)} = 1 $$
    
    $$ 2&Chi;_A = 1 $$
    
    $$ &Chi;_A = 0.5 $$
    
    * Hence, to obtain maximum molar entropy change by mixing two gases A and B, mole fraction of A, &Chi;<sub>A</sub> = 0.5 and mole fraction of B, &Chi;<sub>B</sub> = 0.5, ie, A and B should be equimolar or they should have same number of moles.

??? question "One mole of an ideal gas is expanded isothermally at 298 K until its volume is tripled. Find &Delta;S<sub>gas</sub> and &Delta;S<sub>total</sub> under following conditions: (a) Expansion is reversible (b) Expansion is irreversible where 836.8 J less heat is absorbed than in the first (c) Free expansion"

    * Let's calculate the entropy change for the system or gas.
    
    $$ &Delta;S_{gas} = nRln{V_2 \over V_1} $$
    
    $$ &Delta;S_{gas} = nRln{3V \over V} $$
    
    $$ &Delta;S_{gas} = nRln(3) $$
    
    $$ &Delta;S_{gas} = 1 \times 8.314 \times ln(3) $$
    
    $$ &Delta;S_{gas} = 9.134\ JK^{-1} $$
    
    This is the value of &Delta;S<sub>gas</sub> for all three cases mentioned in the question.
    
    * (a) Since, the process is reversible, &Delta;S<sub>total</sub> = 0. So, &Delta;S<sub>surrounding</sub> = -&Delta;S<sub>gas</sub> = -9.134 JK<sup>-1</sup>
    
    * (b) &Delta;S<sub>surrounding</sub> for irreversible process is given by:
    
    $$&Delta;S_{surrounding} = {-q_{irr} \over T}$$
    
    $$&Delta;S_{surrounding} = {-(q_{rev} - 836.8) \over T}$$
    
    &Delta;S<sub>total</sub> is given by:
    
    $$&Delta;S_{total} = &Delta;S_{gas} + &Delta;S_{surrounding}$$
    
    $$ &Delta;S_{total} = {q_{rev} \over T} + {-(q_{rev} - 836.8) \over T}$$
    
    $$ &Delta;S_{total} = {836.8 \over T}$$
    
    $$ &Delta;S_{total} = {836.8 \over 298} = 2.808\ JK^{-1}$$
    
    * (c) For free expansion, &Delta;S<sub>surrounding</sub> = 0.
    
    $$So,\ &Delta;S_{total} = &Delta;S_{gas} = 9.134\ JK^{-1}$$

??? question "Calculate the entropy change when 0.5 L of an ideal gas (C<sub>v</sub> = 12.6 JK<sup>-1</sup>mol<sup>-1</sup>) at 300 K and 1 atm pressure is allowed to expand to double its volume and simultaneously heated to 373 K."

    Number of moles, n can be calculated by ideal gas equation:
    
    $$n = {PV \over RT}$$
    
    $$n = {1 \times 0.5 \over 0.0821 \times 300} = 0.02$$
    
    Change in entropy, &Delta;S is given by:
    
    $$&Delta;S = nC_vln{T_2 \over T_1} + nRln{V_2 \over V_1}$$
    
    $$&Delta;S = 0.02 \times 12.6 \times ln{373 \over 300} + 0.02 \times 8.314 \times ln{2V_1 \over V_1}$$
    
    $$&Delta;S = 0.17\ JK^{-1}$$

??? question "The temperature of an ideal monoatomic gas is raised from 25<sup>o</sup>C to 250<sup>o</sup>C. What must be the accompanying pressure change in order that the entropy of gas may be unaffected by the complete process?"

    Given values: T<sub>1</sub> = 25 + 273 = 298 K, T<sub>2</sub> = 250 + 273 = 523 K<br>
    
    As per the question, &Delta;S = 0.
    
    $$nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2} = 0$$
    
    $$nC_pln{T_2 \over T_1} = -nRln{P_1 \over P_2}$$
    
    $$ {5R \over 2}ln{T_2 \over T_1} = -Rln{P_1 \over P_2}$$
    
    $$ {5 \over 2} ln{523 \over 298} = ln {P_2 \over P_1}$$
    
    $$ 2.5 ln(1.755) = ln {P_2 \over P_1}$$
    
    $$ln{(1.755)^{2.5}} = ln {P_2 \over P_1}$$
    
    $$ 4 = {P_2 \over P_1}$$
    
    $$P_2 = 4P_1$$
    
    So, final pressure is four times of the initial pressure.

??? question "By how much does the entropy of 3 moles of an ideal gas change in going from pressure of 2 bar to a pressure of 1 bar without any change in temperature? If the surrounding too is at 1 bar pressure and 300 K temperature and the expansion is against the constant external pressure of surroundings, tell whether the process is reversible or irreversible."

    &Delta;S<sub>system</sub> is given by:
    
    $$&Delta;S_{system} = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}$$
    
    $$&Delta;S_{system} = nRln{P_1 \over P_2}$$
    
    $$&Delta;S_{system} = 3 \times 8.314 \times ln{2 \over 1}$$
    
    $$&Delta;S_{system} = 17.29\ JK^{-1}$$
    
    &Delta;S<sub>surrounding</sub> is given by:
    
    $$&Delta;S_{surrounding} = {-q_{irr} \over T}$$
    
    Let's calculate q<sub>irr</sub> by the help of first law of thermodynamics:
    
    $$&Delta;U = q + W$$
    
    $$0 = q_{irr} - P_{ext}(V_2 - V_1)$$
    
    $$0 = q_{irr} - P_{ext}({nRT \over P_2} - {nRT \over P_1})$$
    
    $$q_{irr} = P_{ext} nRT({1 \over P_2} - {1 \over P_1})$$
    
    $$q_{irr} = 1 \times 3 \times 8.314 \times 300({1 \over 1} - {1 \over 2})$$
    
    $$q_{irr} = 3741.3\ J$$
    
    Putting this value in &Delta;S<sub>surrounding</sub>:
    
    $$&Delta;S_{surrounding} = {-3741.3 \over 300} = - 12.47\ JK^{-1}$$
    
    Total change in entropy is given by:
    
    $$&Delta;S_{total} = &Delta;S_{system} + &Delta;S_{surrounding}$$
    
    $$&Delta;S_{total} = 17.29 - 12.47 = 4.82$$
    
    Here, &Delta;S<sub>total</sub> > 0. So, process is spontaneous and irreversible.

??? question "100 g of N<sub>2</sub> gas at 300 K is held by a piston under 30 atm. The pressure is suddenly released to 10 atm and gas is allowed to expand adiabatically. If C<sub>v</sub> is 20.8 JK<sup>-1</sup>mol<sup>-1</sup>, calculate &Delta;S<sub>system</sub>."

    * Moles of N<sub>2</sub>, n = 100/28
    
    * Since, the process is adiabatic, q = 0
    
    * Using first law of thermodynamics:
    
    $$&Delta;U = q + W$$
    
    $$&Delta;U = W$$
    
    $$nC_v(T_2 - T_1) = -P_{ext}(V_2 - V_1)$$
    
    $$nC_v(T_2 - 300) = -10 ({nRT_2 \over P_2} - {nRT_1 \over P_1})$$
    
    $$ n \times 20.8 (T_2 - 300) = -10 ({nRT_2 \over P_2} - {nRT_1 \over P_1})$$
    
    $$ 20.8 (T_2 - 300) = -10 {RT_2 \over P_2} + 10 {RT_1 \over P_1}$$
    
    $$20.8T_2 - (300 \times 20.8) = -10 {8.314 \times T_2 \over 10} + 10 {8.314 \times 300 \over 30}$$
    
    $$20.8T_2 - 6240 = -8.314T_2 + 831.4$$
    
    $$(20.8 + 8.314)T_2 = 6240 + 831.4$$
    
    $$T_2 = {7071.4 \over 29.114} = 243\ K\ (approx.)$$
    
    Change in enthalpy of the system is given by:
    
    $$&Delta;S = nC_pln{T_2 \over T_1} + nRln{P_1 \over P_2}$$
    
    $$&Delta;S = {100 \over 28} \times (20.8 + R) ln {243 \over 300} + {100 \over 28} \times 8.314 \times ln{30 \over 10} $$
    
    $$&Delta;S = 10.71\ JK^{-1}$$

??? question "A certain chemical reaction is spontaneous at 72<sup>o</sup>C. If the enthalpy change for the reaction is 19 KJ, what is the minimum value of &Delta;S for the reaction?"

    Since, the reaction takes place at constant temperature. So, q<sub>rev</sub> = &Delta;H = 19 KJ = 19000 J.
    
    Temperature, T = 72<sup>o</sup>C = (72 + 273)K = 345 K
    
    Change in entropy is given by:
    
    $$&Delta;S = {q_{rev} \over T} = {&Delta;H \over T}$$
    
    $$&Delta;S = {19000 \over 345} = 55.07\ JK^{-1}$$