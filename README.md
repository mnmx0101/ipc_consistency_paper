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

The analysis requires **Python 3.10** and the following packages:

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

The world relies on analyses by the United Nations-facilitated **Integrated Food Security Phase Classification (IPC)** to identify where populations are food insecure and to quantify the severity of crises. IPC subnational analyses are intended to be comparable across regions and time and are used to allocate more than six billion dollars in humanitarian assistance annually.

This paper evaluates whether IPC food insecurity analyses are consistent and comparable. Using 1,849 IPC analyses from fifteen countries (2019–2023), we find that IPC assessments face substantial challenges related to **data availability** and **indicator discordance**. While most analyses follow IPC guidance, the guidance allows a wide range of classifications for the same evidence base.

We also document variation in how indicators are weighted across countries and over time for the same location. Closely correlated food security indicators are not treated as substitutes, suggesting inconsistency in evidence interpretation. These findings have implications for humanitarian policy and the use of IPC analyses by researchers.

---

## Contact

For questions or issues related to this replication package, please contact:

**Chungmann (Manny) Kim** University of Illinois Urbana-Champaign  
Email: **ck24@illinois.edu**
