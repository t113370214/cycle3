# README.md

## 👥 Group Information
* **Group Number:** Group 11
* **Members & Contribution:**
  * **林家昕** | ID: 111370235  
    * *Responsibilities:* **Full Project Execution & Presentation Part I.** Responsible for the entire analytical pipeline, including data cleaning, recoding, exploratory data analysis (EDA), generating all core statistical plots, performing the Two-Proportion Z-Test, and phrasing the final academic conclusion. Solely responsible for writing the technical documentation (`README.md`), structuring and designing the entire layout of the one-page summary poster, and delivering the **background, data setup, and methodology sections** of the video presentation.
  * **吳宗祐** | ID: 113370214  
    * *Responsibilities:* **Presentation Part II & Video Editing.** Assisted in basic layout refinement of the one-page summary poster and responsible for **compiling and editing the final video presentation**. Additionally, responsible for delivering the **exploratory data analysis (all 3 plots and interpretations), statistical inference results, and the short final conclusion sections** of the video presentation.

---

## ❓ Selected Research Question
Is the proportion of current cigarette use different between students who felt sad or hopeless and those who did not?

---

## 🔢 Group Variable and Response Variable
* **Group Variable (Exposed vs. Comparison):**
  * Original Variable: `SadOrHopeless` (Binary)
  * Recoding Schema: $1.0 = \text{Exposed: Code 1 (Yes)}$, $2.0 \rightarrow 0 = \text{Comparison: Code 2 (No)}$
* **Response Variable (Success vs. Failure):**
  * Original Variable: `CurrentCigaretteUse` (Binary)
  * Recoding Schema: $1.0 \rightarrow 0 = \text{Failure (Non-Smoker)}$, $\text{Codes 2-7} \rightarrow 1 = \text{Success (Smoker)}$

---

## 🧪 Method Used
* **Statistical Method:** Two-Proportion Z-Test ($\alpha = 0.05$)
* **Hypotheses:**
  * Null Hypothesis ($H_0$): $p_1 - p_0 = 0$
  * Alternative Hypothesis ($H_a$): $p_1 - p_0 \neq 0$
* **Dataset:** 2007 Youth Risk Behavior Surveillance System (YRBSS) with a valid sample size of $N = 13,174$.
* **Key Statistical Outputs:**
  * $z\text{-statistic} = 15.05$
  * $p\text{-value} = 3.267\text{e-}51$
  * $95\% \text{ Confidence Interval (CI)} = [10.76\%, 12.09\%]$

---

## 📝 Short Final Conclusion
The analysis demonstrates that adolescent students experiencing sadness or hopelessness exhibit an 11.43% higher smoking prevalence compared to those without such emotional distress. This confirms a strong statistically significant association, suggesting that negative emotional health may be a critical risk factor for adolescent cigarette use.
---

## 🎥 Video Presentation & Project Repository
Our recorded video presentation, which covers the data visualization, statistical analysis, and final conclusions, as well as our complete code repository, can be accessed via the links below:

* **Watch the Video Presentation:** [https://youtu.be/U7eaHwyWFkk]
* **View the Source Code on GitHub:** []
