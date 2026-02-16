# Sequestar

## Phytoplankton Bioreactor Equations

1) $ \frac{\delta P}{\delta t} = P_{t} \times \mu_t $

2) $ \mu_t = \mu_{max} \times \frac{NO_3}{K_{NO_3} + NO_3}  \times \frac{PO_4}{K_{PO_4} + PO_4}  \times \frac{HCO_3}{K_{C0_3} + HCO_3} \times tanh\frac{E_z}{E_{K}} $

3) $ Chl_{t} = P_{t} \times \frac{Chl}{C} $

4) $ E_z = E_o \times exp^{0.2 \times Chl} $

## DIC, pH, Alkalinity


### Verspagen (2.12): $ \frac{\delta DIC}{\delta t} = DIC_{t-1} -  \frac{\delta P}{\delta t} + gCO_2 $ 
### Verspagen (2.14): $ ALK = [HCO_3] + 2[CO_3] + [HPO_4] + 2*[PO_4] + [OH] - [H_3PO_4] - [H] $
### Verspagen (2.15): $ \frac{\delta ALK}{\delta t}  = ALK_{t-1}  + (\mu N + \mu P + 2*\mu S) * \frac{\delta P}{\delta t} $

## BG11 Media 
#### $ NaNO_3 = 17.6 mM $
#### $ MgSO_4 = 0.3 mM $
#### $ K_2HPO_4 = 0.22 mM $
#### $ NA_2CO_3 = 0.18 mM $
