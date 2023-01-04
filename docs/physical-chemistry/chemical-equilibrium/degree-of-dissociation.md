---
title: Chemical Equilibrium | Degree of dissociation
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Chemical Equilibrium | Degree of dissociation

## Degree of dissociation (&alpha;)

* Fraction of reactants dissociated is known as degree of dissociation.

!!! tip ""

    $$&alpha; = {{Moles\ of\ reactants\ dissociated \times 100} \over Initial\ moles\ of\ reactants}$$

!!! example "Let us consider an example, in which moles of A given is 2."

    $$ A &#8652; 2B + 3C$$

    $$At\ t=0,\ moles\ of\ A = 2,\ moles\ of\ B = 0,\ moles\ of\ C = 0$$

    At equilibrium:

    $$moles\ of\ A = 2-2&alpha;,\ moles\ of\ B = 2\times 2&alpha;,\ moles\ of\ C = 3\times 3&alpha;$$

??? question "If degree of dissociation of NH<sub>3</sub> is 75%, then calculate the partial pressure of each gas at equilibrium. The total pressure at equilibrium is 1 atm. <br> $2NH_{3_{(g)}} &#8652; N_{2_{(g)}} + 3H_{2_{(g)}}$"

    Let us consider that at t = 0, moles of NH<sub>3</sub> = a, moles of N<sub>2</sub> = 0 and moles of H<sub>2</sub> = 0.
    
    If &alpha; is the degree of dissociation, then at equilibrium, we can calculate:
    
    $$moles\ of\ NH_3 = a - a\ &alpha;$$
    
    $$moles\ of\ N_2 = {{a &alpha;} \over 2}$$
    
    $$moles\ of\ H_2 = {{3a &alpha;} \over 2}$$
    
    $$Total\ moles\ at\ equilibrium = a - a&alpha; + {{a &alpha;} \over 2} + {{3a &alpha;} \over 2} = a(1+&alpha;)$$
    
    $$Partial\ pressure\ of\ NH_3 = {&Chi;_{NH_3} \times Total\ pressure} = {a(1-&alpha;) \over a(1+&alpha;)} \times 1 = {1-0.75 \over 1+0.75} = {1\over7} atm$$
    
    $$Similarly,\ partial\ pressure\ of\ N_2 = {3\over14} atm$$
    
    $$And,\ partial\ pressure\ of\ H_2 = {9\over14} atm$$

## Calculations of K<sub>c</sub> and K<sub>p</sub>

### 1. Reactions with &Delta;n<sub>g</sub> = 0

??? example "Let us consider an example where &Delta;n<sub>g</sub> is zero (decomposition of HI)"

    $$2HI_{(g)} &#8652; H_{2_{(g)}} + I_{2_{(g)}}$$
    
    $$At\ t=0,\ let\ moles\ of\ HI = a$$
    
    $$At\ t=0,\ moles\ of\ H_2\ and\ I_2 = 0$$
    
    If &alpha; is the rate of dissociation ,then at equilibrium:
    
    $$moles\ of\ HI = a - a&alpha;$$
    
    $$moles\ of\ H_2 = {a&alpha;\over 2}$$
    
    $$moles\ of\ I_2 = {a&alpha;\over 2}$$
    
    Also, let the volume of container be V. Then, the concentrations are:
    
    $$Concentration\ of\ HI = {a(1-&alpha;)\over V}$$
    
    $$Concentration\ of\ H_2 = {a&alpha;\over 2V}$$
    
    $$Concentration\ of\ I_2 = {a&alpha;\over 2V}$$
    
    Now we can calculate K<sub>c</sub> as below:
    
    $$K_c = {{[H_2][I_2]}\over{[HI]^2}}$$
    
    $$K_c = {{{a&alpha;\over 2V} \times {a&alpha;\over 2V}} \over ({{a(1-&alpha;)}\over V})^2}$$
    
    $$K_c = {&alpha;^2 \over 4(1 - &alpha;)^2}$$
    
    Also, K<sub>p</sub> is given by:
    
    $$K_p = K_c\ (RT)^{&Delta;n_g}$$
    
    Here, &Delta;n<sub>g</sub> = 0, so we can write:
    
    $$K_p = K_c = {&alpha;^2 \over 4(1 - &alpha;)^2}$$
    
    **K<sub>p</sub> can also be calculated alternatively using the below method:**
    
    $$Total\ moles\ at\ equilibrium = a - a&alpha; + {a&alpha;\over 2} + {a&alpha;\over 2} = a$$
    
    Let total pressure be P and we know that:
    
    $$Partial\ pressure = mole\ fraction \times total\ pressure$$
    
    Hence, we can find partial pressure of each gas as:
    
    $$P_{H_2} = {a&alpha;\over 2a} \times P = {P&alpha; \over 2}$$
    
    $$P_{I_2} = {a&alpha;\over 2a} \times P = {P&alpha; \over 2}$$
    
    $$P_{HI} = {{a(1-&alpha;)\over a} \times P} = P(1-&alpha;)$$
    
    $$K_p = {{P_{H_2} \times P_{I_2}} \over (P_{HI})^2} = {&alpha;^2 \over {4(1-&alpha;)^2}}$$

### 2. Reactions with &Delta;n<sub>g</sub> > 0

??? example "Let us consider an example where &Delta;n<sub>g</sub> > 0 (decomposition of PCl<sub>5</sub>)"

    $$PCl_{5_{(g)}} &#8652; PCl_{3_{(g)}} + Cl_{2_{(g)}}$$
    
    $$At\ t=0,\ let\ moles\ of\ PCl_5 = a$$
    
    $$At\ t=0,\ moles\ of\ PCl_3\ and\ PCl_5\ = 0$$
    
    If &alpha; is the rate of dissociation, then at equilibrium:
    
    $$moles\ of\ PCl_5 = a-a&alpha;$$
    
    $$moles\ of\ PCl_3 = a&alpha;$$
    
    $$moles\ of\ Cl_2 = a&alpha;$$
    
    If volume of container is V, then the concentrations at equilibrium:
    
    $$Concentration of PCl_5 = {a-a&alpha; \over V}$$
    
    $$Concentration of PCl_3 = {a&alpha; \over V}$$
    
    $$Concentration of Cl_2 = {a&alpha; \over V}$$
    
    $$K_c = {[PCl_3][Cl_2]\over [PCl_5]}$$
    
    $$K_c = {{a&alpha;\over V}\times{a&alpha;\over V}\over{a(1-&alpha;)\over V}} = {a&alpha; \over (1-&alpha;)V}$$
    
    Now, let us calculate K<sub>p</sub> in terms of pressure. Let the total pressure be P.
    
    $$Total\ moles\ at\ equilibrium = a-a&alpha;+a&alpha;+a&alpha; = a(1+&alpha;)$$
    
    We know that partial pressure = mole fraction * Total Pressure. Hence:
    
    $$P_{PCl_3} = {{a&alpha;\over a(1+&alpha;)} \times P} = {P&alpha;\over(1+&alpha;)}$$
    
    $$P_{Cl_2} = {{a&alpha;\over a(1+&alpha;)} \times P} = {P&alpha;\over(1+&alpha;)}$$
    
    $$P_{PCl_5} = {{a(1-&alpha;)\over a(1+&alpha;)}\times P} = {P(1-&alpha;)\over (1+&alpha;)}$$
    
    We can calculate K<sub>p</sub> as:
    
    $$K_p = {{P_{PCl_3} \times P_{Cl_2}} \over P_{PCl_5}}$$
    
    $$K_p = {{P&alpha;\over (1+&alpha;)} \times {P&alpha;\over (1+&alpha;)} \over {P(1-&alpha;)\over(1+&alpha;)}}$$
    
    $$K_p = {P&alpha;^2 \over (1-&alpha;^2)}$$

### 3. Reactions with &Delta;n<sub>g</sub> < 0

??? example "Let us consider a reaction in which &Delta;n<sub>g</sub> is less than 0."

    $$N_{2_{(g)}} + 3H_{2_{(g)}} &#8652; 2NH_{3_{(g)}}$$
    
    At time t = 0, let the moles of N<sub>2</sub> and H<sub>2</sub> be a and moles of NH<sub>3</sub> be 0.
    
    Now, if &alpha; is the degree of dissociation, then at equilibrium:
    
    $$moles\ of\ N_2 = a - {1 \over 3}a&alpha;$$
    
    $$moles\ of\ H_2 = a - a&alpha;$$
    
    $$moles\ of\ NH_3 = {2\over 3} a&alpha;$$
    
    Let the volume of container be V. Now, we can calculate K<sub>c</sub> as shown below:
    
    $$K_c = {[NH_3]^2 \over [N_2] [H_2]^3}$$
    
    $$K_c = {({2a&alpha;\over 3V})^2 \over ({a-{a&alpha;\over 3} \over V}) \times ({a-a&alpha;\over V})^3 }$$
    
    $$K_c = {4&alpha;^2V \over 3a(3-&alpha;)(1-&alpha;)^2}$$
    
    !!! question "Can you calculate K<sub>p</sub> for this reaction in terms of total pressure P?"

