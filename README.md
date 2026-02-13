# (CAD) Breach-Cost-Simulator

> **Visualizing the financial and operational gravity of a cyber incident through a Canadian lens.**

<h3 align="center">
  <a href="https://ironbranded.github.io/CAD-Breach-Cost-Simulator/" target="_blank" rel="noopener noreferrer">
    🟢 LAUNCH THE SIMULATOR 🟢
  </a>
</h3>

---

### ⚠️ DISCLAIMER
> *This simulator is a financial modeling tool intended for **educational and risk-awareness purposes only!***
>
> Estimated figures are based on **2025-2026 Canadian industry benchmarks**.
> Please note that actual incident costs can vary significantly depending on factors including, but not limited to, insurance coverage, regulatory fines, response time, the nature of the affected data, and applicable service rates.
---

## Executive Overview

In the current threat landscape, a "breach" is more than just downtime; it is a multi-level financial event. 

> **Why this tool?**
> As a Tactical DFIR Hunter in training, I came to realize that DFIR is not just about the "bits and bytes", it's also about understanding the potential business impact. This tool helps bridge the gap between technical and executive risk management.

### Key Calculation Vectors

* **Incident Scenarios:** Ransomware (Double Extortion), BEC, Data Leaks, and Insider Threats.
* **Industry Multipliers:** Specialized weighting for High-Risk sectors (Healthcare, Finance, Energy).
* **Regulatory Impact:** Built-in logic on some of the popular regulatory notification costs.
* **Operational Loss:** Real-world downtime estimates based on 2025 Canadian benchmarks.

---

## Logic

The simulation logic is informed by a combination of industry-standard reports (IBM, Sophos, Coveware, CSE).

### The Formula Approach

The simulator uses a weighted impact matrix:

$$
\text{Total Cost} = (\text{Tech Response}) + (\text{Legal / Regulatory}) + (\text{Business Impact})
$$

### Cost Vectors

| Vector | Rate / Logic |
| :--- | :--- |
| **Technical IR** | Calculated at an IR rate of **$300/hr**. |
| **Legal Counsel** | Privacy Coach / Breach Counsel rates at **$500/hr**. |
| **Fraud / Extortion** | Scaled based on annual revenue brackets and data volume. |



### Insurance Logic & Parameters

The tool allows the input of specific policy parameters to model a realistic recovery scenario:
* **Coverage Limit:** The maximum aggregate amount the insurer will pay.
* **Deductible (Retention):** The out-of-pocket amount the organization must pay before insurance triggers.


---

## Data Privacy

This tool is built as a static, client-side web page.

* **Local Execution:** All drill-down logic and financial calculations occur exclusively within the user's browser.
* **No Transmission:** No information is transmitted to external servers, databases, or APIs.
* **No Tracking:** No cookies or persistent tracking mechanisms are utilized.

---

### Author
**M.Decayette (IronBranded)**
