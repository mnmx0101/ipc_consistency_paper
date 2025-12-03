# Inside the Black Box: How Consistent Are Global Food Security Crisis Assessments?

## Overview
This repository contains the replication materials for the paper:

**Inside the black box: how consistent are global food security crisis assessments?**

The study evaluates whether food insecurity analyses conducted through the **Integrated Food Security Phase Classification (IPC)** system are consistent and comparable across time and space. We analyze **1,849 subnational IPC analyses** from **15 countries** covering **742 million people** (2019–2023) and document how variation in data availability and indicator discordance affects IPC classifications.

Because humanitarian agencies rely heavily on IPC outputs, understanding their internal consistency has direct implications for funding decisions, early warning, and food security research.

## Data Availability

**Important:** The IPC datasets used in this paper are **restricted** and **cannot be shared publicly**.

* This repository does **not** include the underlying `.csv` files.
* The folder `stores/` indicates where authorized users should place the required data locally.
* With access to the data, the full analysis can be reproduced.

The complete replication code is available in:
**`script/inside_the_blackbox_replication_code.ipynb`**

This script reproduces all figures, tables, and results from the paper.

---

## How to Run the Replication Code

1. Obtain IPC subnational datasets (restricted access).
2. Place all required `.csv` files in the folder:
   `stores/`
3. Open and run:
   `script/inside_the_blackbox_replication_code.ipynb`

---

## Software Requirements

The analysis requires the following packages:

pandas==1.1.3

numpy==1.19.5

seaborn==0.12.2

statsmodels.api==0.13.5

matplotlib==3.3.2

statsmodels==0.13.5

stata_setup==0.1.3

A standard **Anaconda environment** works well. One can use the `requirements.txt` to set up the environment.

---

## Abstract

The world relies on analyses by the United Nations-facilitated Integrated Food Security Phase Classification (IPC) to identify where populations are food insecure and to quantify the severity of these crises. IPC sub-national analyses are designed to be comparable over space and time in the more than 30 countries in which they operate. Humanitarian agencies appear to treat these findings as authoritative and comparable, and as of 2023, relying on IPC analyses to allocate more than six billion dollars of aid per year. In this paper, we study whether IPC food insecurity subnational analyses  are indeed consistent and comparable across time and space. Analyzing 1,849 IPC subnational analyses covering 742 million people from fifteen countries between 2019 and 2023, we show that IPC subnational analyses  face significant challenges related to data availability and food security measurement, resulting from often discordant underlying food security indicators. We find that the vast majority of IPC subnational analyses are consistent with IPC technical guidance, but that this guidance permits a wide range of classifications for a given set of food security indicators. We also find evidence that IPC subnational analyses differ in the way they use food security data, often weighing food security indicators differently in different locations. While variation in how food security indicators are used can reflect varying contextual factors across countries, we find evidence that indicators are weighed differently across time for the same location in analyses . Finally, we show that closely correlated food security indicators are not treated as substitutes, suggesting inconsistency in the treatment of food security indicators across analyses. We discuss implications of these findings for policy and for the use of IPC analyses by researchers and policymakers

---

## Contact

For questions or issues related to this replication package, please contact:

**Chungmann (Manny) Kim** University of Illinois Urbana-Champaign  
Email: **ck24@illinois.edu**
