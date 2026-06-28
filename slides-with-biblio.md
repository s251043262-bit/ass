---
title-slide: false
bibliography: references.bib
csl: vancouver.csl
citeproc: true
theme: serif
background-color: "#ffffff"
transition: slide
navigationMode: linear
hash: true
---

:::: {.columns}
::: {.column width="50%"}

## Statistical Analysis of Part Resistance
#### Machine Analysis Report
#### Universiti Malaysia Perlis
#### s251043262@studentmail.unimap.edu.my

:::

::: {.column width="50%"}
![](media/pics/logo1.png)
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Resistance by Machine
**Statistical Analysis:**
- **Machine 1 Average:** 5.3712
- **Observation:** Analysis focuses on Machine 1 performance consistency.
- Distribution shows variance across different operational units.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/boxplot_resistance_by_machine.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Resistance by Temperature
**Statistical Analysis:**
- **Significance:** p-value ≈ 0.0000
- **Result:** Temperature is **highly significant** in affecting Part Resistance.
- Higher temperature levels correlate with noticeable shifts in resistance distribution.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/boxplot_resistance_by_temperature.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Resistance by Pressure
**Statistical Analysis:**
- **Significance:** p-value = 0.8970
- **Result:** Pressure is **not statistically significant** for Machine 1.
- **Interaction (P*T):** p-value = 0.7349 (Not Significant).
:::

::: {.column width="50%"}
<iframe data-src='media/plots/boxplot_resistance_by_pressure.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---
# Bibliography
<div id="refs"></div>
