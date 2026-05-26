# Data-Science-Consulting-Project-Hackathon
## Hill's Pet Nutrition: Media Mix Modeling & Data Clean Room Optimization Engine

Welcome to the Advanced Marketing Econometrics and Data Privacy section of my portfolio. This repository contains the complete data science pipeline, code, and consulting frameworks built for the **Audencia Data Hackathon**. Acting as a strategic data consultant for **Hill's Pet Nutrition (Colgate-Palmolive)**, this project builds an econometric allocation engine to navigate a cookieless marketing landscape, analyze cross-channel advertising diminishing returns, and reallocate multi-million dollar budgets to maximize revenue.

---

## Project Architecture & Business Intelligence
**Files:** `PPT-Grp-work.pdf` (Executive Deck) | `Grp_DS_Consulting_Project_All.ipynb` (Production Code Script) | `Grp_DS_Consulting_Project_Aggregated.ipynb` (Aggregated MMM Module)

With the depreciation of third-party cookies, consumer packaged goods (CPG) brands face a severe tracking blind spot connecting digital impressions to offline retail checkouts. This project solves that dilemma in two distinct phases: designing a privacy-safe data ecosystem and executing advanced statistical media mix modeling.

### Phase 1: The Strategic Data Collaboration Ecosystem
To establish closed-loop measurement, I designed a multi-stakeholder **Data Clean Room (DCR)** environment utilizing secure infrastructure frameworks (e.g., Snowflake, Habu, LiveRamp):
* **Hill's (1st-Party CRM Data):** Supplies precise pet archetype profiles and direct brand loyalty interactions.
* **Petco/Petsmart (2nd-Party Transactional Data):** Contributes specialized health-retail purchasing behaviors via loyalty programs and in-store veterinary point-of-sale logs.
* **Meta/Publisher Networks (3rd-Party Interaction Data):** Feeds granular, deterministic, user-level impression streams.

---

### Phase 2: Econometric Modeling & Saturation Curves

Using granular media exposure datasets alongside mass retailer transactional records ($N > 62 \text{ Million}$ total sales value), this engine evaluates the true operational efficiency of **TV vs. Programmatic Ad Channels**.

#### 1. Mathematical Budget Saturation & Diminishing Returns
Advertising response is non-linear. To uncover where marginal returns deteriorate, I modeled spending trajectories using non-linear econometric curves (Logarithmic and Michaelis-Menten functional forms):

$$Sales = \alpha + \beta \cdot \ln(Spend + 1)$$

This isolates the point where ad repetition shifts from customer acquisition to wasteful, oversaturated budget burn.

#### 2. Core Analytical Findings & Marginal ROAS (mROAS)
* **The TV Efficiency Crisis:** TV spending was heavily over-allocated ($\$1.148\text{M}$). Due to steep historical saturation, its current **Marginal ROAS dropped to $-0.038\times$**, meaning additional dollars spent on TV resulted in a net loss.
* **The Programmatic Alpha Channel:** Programmatic ad distribution ($\$787\text{K}$) maintained a massive, linear headroom trajectory with a blistering **Marginal ROAS of $102.66\times$**.

#### 3. Optimized Budget Reallocation Scenario
By running an optimization scenario that executes a **10% budget pivot out of TV ($-\$114\text{K}$) directly into Programmatic channels**, the framework achieves a dramatic revenue lift without changing the overall marketing budget:
* **TV Sales Loss:** Minimal friction impact ($-\$17.5\text{K}$)
* **Programmatic Sales Gain:** Massive top-line acceleration ($+\$344.3\text{K}$)
* **Net Performance Yield:** **$+\$326.7\text{K}$ in incremental sales** ($+2.23\%$ total brand lift)

---

## Tech Stack & Advanced Competencies
* **Marketing Econometrics:** Media Mix Modeling (MMM), Diminishing Return Curves, Saturation Thresholds, Marginal ROAS Calculations.
* **Data Privacy Infrastructure:** Data Clean Room Strategy, Cryptographic ID Mapping, Privacy-Safe Multi-Party Computation.
* **Programming Stack:** Python 3 (Pandas, NumPy, Scikit-Learn, SciPy Optimization Modules).
* **Data Visualization:** Advanced Matplotlib, Custom Dual-Axis Saturation Plotting, Seaborn.
