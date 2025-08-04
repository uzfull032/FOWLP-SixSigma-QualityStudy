# FOWLP-SixSigma-QualityStudy
six sigma methodologies

---

## 🧪 Abstract
In this study, we investigated how inlet structures and baffle configurations within the FOWLP (Fan-Out Wafer Level Packaging) chamber affect wafer coating quality. Using Six Sigma-based statistical analysis (Cp, Cpk, Z-score, and DPMO), we quantitatively evaluated the film uniformity of wafers experimentally manufactured under various chamber designs. The results showed that the inclusion of a baffle and optimized slit-type inlet significantly enhanced process capability and coating consistency.

---

## 📐 Mathematical Method
The wafer film quality was analyzed using Six Sigma statistical indicators as follows:
<p align="left"><img width="533" height="511" alt="image" src="https://github.com/user-attachments/assets/48e0f5d8-3246-4538-8d35-b30ddf0843e0" />

The evaluation of manufactured wafers
<p align="left"><img width="480" height="138" alt="image" src="https://github.com/user-attachments/assets/52d6770d-890d-42a8-b0d1-976eb1f52630" />

Applied overall chambers
<p align="left"><img width="478" height="181" alt="image" src="https://github.com/user-attachments/assets/84159621-a392-46a5-8869-1bcceae54458" />


---

## 📊 Key Results Summary Table

| Chamber Type      | Structure      | Outlet Pressure | Cp    | Cpk   | Z-score | DPMO     |
|-------------------|----------------|------------------|--------|--------|---------|-----------|
| **Hole (Original)**    | Non-baffle     | 0.05 kPa         | 0.51   | 0.26   | 0.79    | 160,000   |
|                   |                | 0.15 kPa         | 0.52   | 0.34   | 1.01    | 240,000   |
|                   | With baffle    | 0.05 kPa         | 0.59   | 0.45   | 1.35    | 80,000    |
|                   |                | 0.15 kPa         | 0.54   | 0.47   | 1.41    | 120,000   |
| **Slit (Original)**    | Non-baffle     | 0.05 kPa         | 0.22   | 0.06   | 0.17    | 380,000   |
|                   |                | 0.15 kPa         | 0.34   | 0.19   | 0.19    | 380,000   |
|                   | With baffle    | 0.05 kPa         | **1.35** | **0.85** | **2.54** | **40,000** |
|                   |                | 0.15 kPa         | 0.75   | 0.64   | 1.91    | 60,000    |
| **Hole (Modified)**   | Non-baffle     | 0.05 kPa         | 0.58   | 0.45   | 1.35    | 100,000   |
|                   |                | 0.15 kPa         | 0.24   | 0.12   | 0.36    | 540,000   |
|                   | With baffle    | 0.05 kPa         | 1.03   | 0.62   | 1.87    | 80,000    |
|                   |                | 0.15 kPa         | 0.40   | 0.30   | 0.91    | 220,000   |
| **Slit (Modified)**   | Non-baffle     | 0.05 kPa         | 0.60   | 0.58   | 1.75    | 100,000   |
|                   |                | 0.15 kPa         | 0.58   | 0.30   | 0.91    | 220,000   |
|                   | With baffle    | 0.05 kPa         | **1.79** | **1.11** | **3.33** | **0**       |
|                   |                | 0.15 kPa         | 1.02   | 0.52   | 1.57    | 120,000   |
| **Plain (Modified)**  | Non-baffle     | 0.05 kPa         | 0.87   | 0.69   | 2.06    | 60,000    |
|                   |                | 0.15 kPa         | 0.70   | 0.42   | 1.25    | 140,000   |
|                   | With baffle    | 0.05 kPa         | 0.71   | 0.40   | 1.19    | 80,000    |
|                   |                | 0.15 kPa         | 0.40   | 0.06   | 0.18    | 340,000   |

> ✅ **Best Performance**: Modified Slit with Baffle at 0.05 kPa (Cp = 1.79, Cpk = 1.11, Z = 3.33, DPMO = 0)

---

## 📊 Representative Figures

<p align="left">
  <img width="958" height="570" alt="image" src="https://github.com/user-attachments/assets/b9d6512f-bbcb-418c-b89d-d7aa13f748cf" />
  <img width="958" height="570" alt="image" src="https://github.com/user-attachments/assets/095b402f-83e5-4383-a944-8c546c5b9a82" />
  <img width="998" height="507" alt="image" src="https://github.com/user-attachments/assets/ef770e15-2a7c-4556-8312-3bc32823d51d" />
  <img width="998" height="507" alt="image" src="https://github.com/user-attachments/assets/c934e9db-1c12-4197-9330-68c1c0dbd99f" />
  
  **Above pictures are manufactured wafer results**
</p>
<p align="left">
  <img width="1114" height="652" alt="image" src="https://github.com/user-attachments/assets/480d1248-8508-435b-8415-e1e9bac89526" />
  <img width="1114" height="652" alt="image" src="https://github.com/user-attachments/assets/b547bc84-5842-4879-9bed-54b6a344b6be" />
  <img width="883" height="350" alt="image" src="https://github.com/user-attachments/assets/a3d8ea5a-2f49-4d9f-9612-26c825ec3999" />
  <img width="883" height="350" alt="image" src="https://github.com/user-attachments/assets/142a7cb6-35be-43f3-8b49-46ebf7292317" />
  <img width="883" height="350" alt="image" src="https://github.com/user-attachments/assets/11449c3b-b21a-468c-a21b-11d3a93aacd7" />

  **Above pictures are manufactured wafer results, Not inclueded in my thesis**
</p>
---

## 🔍 Conclusion
The Six Sigma-based evaluation revealed that both inlet structure and baffle presence play a significant role in wafer film uniformity. While traditional hole-type chambers exhibited large variation and low process capability, the modified slit-type chambers with baffle under low-pressure (0.05kPa) conditions yielded the most favorable results.
These findings suggest that the **slit + baffle + ring-type inlet** combination should be considered as a standard guideline in future FOWLP bake chamber designs. Further improvements are still necessary to fully meet industrial Six Sigma standards, but the current results show promising trends for process optimization and repeatability.

---
