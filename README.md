# Mini-Project 2 — MediCare Outpatient Visits: End-to-End Data Analysis

**Python for Full Stack Data Science with AI & Generative AI · Naresh IT · Lead Trainer: Ajit Byru**

You are the data analyst for MediCare's outpatient clinic. The administrator has one year of visit records and needs answers she can act on in 2026. Your job: clean the data honestly, answer five guided questions with charts, investigate one question of your own, and present a recommendation.

## Files

| File | What it is |
|---|---|
| `clinic_visits_2025.csv` | Raw export — ~2,400 visits, deliberately messy |
| `clinic_visits_analysis_student.ipynb` | Your notebook. Fill every `# YOUR CODE HERE` and every *Reading:* line |
| `README.md` | This file — becomes the README of your GitHub repo |

## Rules

- **No `sklearn`, no models.** Insight, not prediction. Module 16 is next.
- Every cleaning decision goes in the **Data-Quality Log** with rows affected and *why this fix rather than another*.
- Every question ends in a **chart with a title, axis labels, and a one-sentence reading**.
- Notebook must run top-to-bottom in a fresh kernel (Runtime → Restart and run all) before submission.
- Use AI assistants for syntax, not for decisions. In the viva you will be asked to explain any line.

## Definition of done

- [ ] Data-Quality Log has 7 rows, each with rows affected and a reason
- [ ] Final clean shape printed and matches the acceptance number given in class
- [ ] Q1–Q5 each have a chart and a *Reading:* sentence
- [ ] Own question: one `groupby`, one chart, one defended statistic, one "what I'd need to be sure"
- [ ] Recommendation paragraph, 120–180 words, addressed to the administrator
- [ ] Five slides (template below) as PDF or PPTX
- [ ] README: cleaning-log summary + answers to the five interview questions
- [ ] Notebook runs clean from a fresh kernel

## The five-slide template

| Slide | Title | Content |
|---|---|---|
| 1 | The question | One sentence: what the administrator asked. One line: the data (rows, period, columns). |
| 2 | Data & cleaning | The 7-row log as a compact table. Bold the one decision you're proudest of. |
| 3 | Three findings | Three charts, three one-line readings. One must be from your own question. |
| 4 | Recommendation | The paragraph, cut to 3 bullets + the one number that proves it. |
| 5 | What I'd do next | What you'd check with more data · one thing you'd change · "Next: predict consult time from age + department + doctor". |

**Two-minute pitch order:** slide 1 (15 s) → slide 3 (60 s) → slide 4 (30 s) → slide 5 (15 s). Skip slide 2 unless asked.

## The five interview questions (answer these in your README)

1. **Why did you keep the ₹50,000 fees when the outlier rule flagged them?**
2. **Your first date parse produced 83 Sunday visits. How did you catch it, and how did you fix it?**
3. **Why per-department median for missing fees instead of the overall median or the mean?**
4. **Cardiology's mean fee is ₹2,021 and its median is ₹1,260. Which one goes in the annual report?**
5. **What is one decision in your log you would change if you had more data?**

## Grading (20 marks)

| Criterion | Marks |
|---|---|
| Data-Quality Log — problems found, fixes justified | 5 |
| Q1–Q5 correct, charted, read | 5 |
| Own question — depth and defended statistic | 3 |
| Recommendation paragraph — specific, numeric, actionable | 3 |
| Reproducibility & hygiene — fresh-kernel run, README, slides | 2 |
| Viva & pitch | 2 |

## Setup

Works in Google Colab (upload the CSV) or locally:

```bash
pip install numpy pandas matplotlib jupyter
jupyter notebook clinic_visits_analysis_student.ipynb
```
Works in Google Colab (upload the CSV) or locally:

```bash
pip install numpy pandas matplotlib jupyter
jupyter notebook clinic_visits_analysis_student.ipynb
```
