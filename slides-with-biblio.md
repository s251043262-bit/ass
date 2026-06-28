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
#### LEONG XIN YI
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
**1. Machine Baseline Analysis:**
- **Target:** Machine 1 Consistency.
- **Finding:** Machine 1 Average Resistance is **5.3712**.
- **Context:** The analysis focuses on ensuring Machine 1 operates within specified tolerances.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/boxplot_resistance_by_machine.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Resistance by Temperature
**2. Significant Driver Identification:**
- **ANOVA p-value:** ≈ 0.0000
- **Conclusion:** Temperature is the **primary significant factor** affecting Part Resistance.
- Higher temperatures lead to a distinct upward shift in resistance levels.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/boxplot_resistance_by_temperature.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---

:::: {.columns}
::: {.column width="50%"}
### Resistance by Pressure
**3. Secondary Factor Analysis:**
- **ANOVA p-value:** 0.8970
- **Conclusion:** Pressure is **not statistically significant** for Machine 1.
- **Interaction (P*T):** p-value = 0.7349 (Not Significant).
- Findings suggest pressure settings do not require adjustment for resistance stability.
:::

::: {.column width="50%"}
<iframe data-src='media/plots/boxplot_resistance_by_pressure.html' width='100%' height='500px' style='border:none;'></iframe>
:::
::::

---
# Bibliography
<div id="refs"></div>
