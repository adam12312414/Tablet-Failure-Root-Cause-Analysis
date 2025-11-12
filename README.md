# 💊 Assessing the Root Cause of Tablet Failures  
**Author:** Adam Haizad Bin Mohamad Faizal (2302276G)  
**Module:** IDL – Data Visualization and Storytelling (Group 16)

---

## 📘 Project Overview

## 📘 Project Overview
This Tableau dashboard investigates the **root causes of tablet weight and uniformity failures** observed during a pharmaceutical production process.  

This project was developed in collaboration with **students from the Diploma in Pharmaceutical Science**, combining data analytics and pharmaceutical process knowledge to investigate tablet quality issues.

The analysis identifies the relationship between **process parameters (time, temperature, humidity, and granule size)** and **tablet quality**, offering actionable insights to reduce product variation and improve stability.

The dashboard uses visual storytelling to systematically evaluate test results, environmental conditions, and process metrics — leading to a clear conclusion and set of recommendations.

---

## 🎯 Objectives
- Identify **time points** where tablets failed the uniformity test.  
- Examine the **influence of process factors** such as temperature, humidity, and weight.  
- Determine **environmental and mechanical factors** contributing to failure.  
- Recommend **process improvements** to prevent future inconsistencies.

---

## 🧩 Dashboard Highlights

### 1️⃣ Identifying Failure Points  
The **Uniformity Test Results** show that time points **270 min, 315 min, and 450 min** failed the double-deviation threshold.  
> These time points mark critical process deviations requiring investigation.

---

### 2️⃣ Analyzing Granule Sizes  
The dataset shows a **wide granule size range (600 – 1180 µm)** and poor flow characteristics  
(**Hausner = 1.35, Compressibility = 25**).  
> This suggests challenges in powder segregation and die-filling, which may cause non-uniform tablet weights.

---

### 3️⃣ Assessing Environmental Effects  
#### 🌡️ Temperature  
Temperature rises steadily from **25.1 °C → 26.3 °C** as time increases.  
> Failing tablets occur at higher temperatures, indicating potential thermal sensitivity.

#### 💧 Relative Humidity  
Humidity decreases from **61.5 % → 58.5 %** over time.  
> Lower humidity is associated with higher temperature and greater risk of poor powder flow.

#### 📏 Height  
No direct correlation between tablet height and time points was found.  
> Height consistency indicates that weight and flow properties, not compression, are the main issue.

---

### 4️⃣ Evaluating Tablet Weight  
Average tablet weight fluctuates between **61.7 mg and 65.1 mg**.  
> Failures occur when weight drops below **63 mg**, highlighting the need for tighter weight control.

---

### 5️⃣ Visualizing Outliers  
Box plots show **outliers at 450 min**, with a tablet weighing only **50 mg** compared to the mean of **63 mg**.  
> This extreme deviation indicates possible **segregation during powder flow** from the hopper to the die-fill stage.

---

### 6️⃣ Discovering Trends Across Tablets  
Line plots for time points **270 min, 315 min, 450 min** reveal large fluctuations and uneven tablet weight distribution.  
> Suggests inconsistent filling caused by **granule segregation and poor powder flow**.

---

### 7️⃣ Environmental Conclusion  
Environmental trends (temperature ↑ / humidity ↓) were analyzed side-by-side.  
> The conclusion: **environmental changes contribute**, but are **not the main cause** of failures.

---

### 8️⃣ Identifying the Main Cause  
Both **box plots and line trends** confirm that failures at 270 min, 315 min, 450 min are linked to  
> 🧪 **Granule segregation** and **poor flow properties**  
rather than equipment or environmental malfunction.

---

### 9️⃣ Process Optimization  
The analysis recommends keeping production temperature between **24.5 °C – 25.5 °C** to ensure tablet stability.

> **Ideal tablet weight:** 64 – 66 mg  
> Maintaining this range minimizes deviation and ensures uniformity.

---

### 🔟 Conclusion & Recommendations  

#### ✅ Conclusion  
- Failures were caused by the **combined effects of granule segregation and poor powder flow**.  
- **Environmental factors** (temperature & humidity) played a secondary role.  

#### 💡 Recommendations  
- Add **glidants** (e.g., *silicon dioxide, cornstarch, talc*) to improve powder flow.  
- Increase the **frequency of in-process checks** for tablet weight, hardness, and flow properties.  
- Implement early detection of deviations at critical time points.

---

## 🧠 Key Insights Summary
| Focus Area | Observation | Insight |
|-------------|--------------|---------|
| **Uniformity Test** | Failures at 270 min, 315 min, 450 min | Indicates instability during these time points |
| **Granule Size** | 600 – 1180 µm, poor flow (Hausner 1.35) | Powder segregation likely cause |
| **Temperature** | Rises 25.1 °C → 26.3 °C | Elevated temperature contributes to failure |
| **Humidity** | Drops 61.5 % → 58.5 % | Correlates with reduced flowability |
| **Weight** | Outlier = 50 mg at 450 min | Confirms uneven filling |
| **Recommendation** | Add glidants, tighten weight control | Improves uniformity and reduces deviation |

---

## 🧰 Tools & Techniques
- **Tableau Desktop 2024.x** – Interactive visualization & storyboarding  
- **Excel / CSV** – Data cleaning and structuring  
- **Statistical Visualization** – Box plots, line trends, scatter and distribution charts  
- **Storytelling Techniques** – Sequential analysis from detection → root cause → solution  

---

## 🚀 How to Open
1. Download the Tableau file (`Group16_IDL_Tableau.twbx`).  
2. Open with **Tableau Desktop** or **Tableau Public Desktop**.  
3. Navigate through the story sequence tabs:
   - Uniformity Test Results  
   - Environmental Influence  
   - Weight and Granule Analysis  
   - Main Cause Identification  
   - Recommendations & Conclusion  

---


## 👤 Author
**Adam Haizad Bin Mohamad Faizal**  
Temasek Polytechnic – School of Informatics & IT  
Diploma in Big Data & Analytics (T60)
**Collaborators:** Students from the Diploma in Pharmaceutical Science  
Temasek Polytechnic – School of Applied Science



## ⚠️ Disclaimer
> All data in this project is **simulated** and used purely for **educational purposes** as part of Temasek Polytechnic coursework.  
> It does **not** represent any real pharmaceutical manufacturing data or confidential information.
