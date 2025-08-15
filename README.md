 📘 Task 06 – Descriptive Statistics using LLMs (RSDK 6)

 🧠 Objective

This research task explores how effectively a Large Language Model (LLM) like ChatGPT can interpret and answer natural language questions about a structured real-world dataset. For this task, I used the **2024 Syracuse University Women’s Lacrosse team statistics** as the base dataset and evaluated the LLM’s ability to extract facts, reason over performance, and handle ambiguous queries.

The project is part of ongoing research (RSDK 6) and includes both basic descriptive prompts and expanded, strategic analyses.

---

# 📂 Dataset

Source: Official stats from Syracuse University Athletics  
- 📄 [2024SUStats.pdf](https://cuse.com/sports/2013/1/16/WLAX_0116134638)
- ❗ Dataset not included in this repo per guidelines. Link provided for reproducibility.

---

Prompt Categories

Basic Prompt Set (Original Task 5)
- Total games played
- Overall win-loss record
- Shooting accuracy
- Overtime losses
- Goals per quarter
- Attendance insights
- Shot clock violations
- Patterns in wins vs losses

📄 See full results in: `Task 5 2024 Syracuse Women.docx`

---

Expanded Prompt Set (RSDK 6 – Ongoing)

| # | Prompt | Type | Outcome |
|--|--------|------|---------|
| 11 | Who was the most improved player? | Strategic | ❌ Not answerable from team PDF |
| 12 | Should Syracuse focus on offense or defense to win 2 more games? | Analytical | ✅ Defense, based on OT losses |
| 13 | Which quarter had most defensive breakdowns? | Reasoning | ✅ 4th quarter |
| 14 | Was the team clutch under pressure? | Ambiguous | ❌ Requires prompt rephrasing |
| 15 | How was the team's momentum throughout the season? | Inference | ✅ Strong mid-season, faded late |

📄 See full write-up in: `Expanded_LLM_Results.docx`

---

 Key Skills Applied

- Prompt Engineering  
- Data Interpretation & Reasoning  
- Analytical Thinking with Sports Data  
- Validation of LLM Output  
- Reporting in Structured Format  

---

 📎 Repository Structure

