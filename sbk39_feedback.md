# CW1 Feedback — sbk39

This feedback explains your marks task by task.

## Overall

- Total mark: `77/100`

Task summary:
- Task 1: `5/8`
- Task 2: `6/8`
- Task 3: `8/12`
- Task 4: `4/6`
- Task 5: `8/14`
- Task 6: `13/14`
- Task 7: `5/6`
- Task 8: `11/12`
- Task 9: `10/12`
- Task 10: `7/8`

---

## Task 1

Mark: `5/8`

What was done well:

- You correctly removed duplicates from the required tables.
- You used the correct tables and join keys.
- Your written explanation clearly explained why both kinds of duplicates matter for the analysis.

What was partly correct:

- There was no partly-correct middle ground on this task.

What lost marks:

- The final matched joined dataset was not correct, so this was the main source of lost marks in Task 1. Full credit here required using `inner_join` so that only matched records were retained. In your submitted solution, you used `left_join`.

What would have improved this further:

- Full credit required the correctly matched final joined dataset using `inner_join`, together with a short clear explanation of why duplicates in each source can distort the merged analysis.

---

## Task 2

Mark: `6/8`

What was done well:

- You correctly summarised the missing-data pattern.
- You correctly calculated the median rating.

What was partly correct:

- Your written explanation showed a good understanding of the character / string missingness issue, but it needed either clearer explanation or stronger evidence for full credit.

What lost marks:

- The deductions on this task came from the partly-correct points noted above, which were not complete enough for full credit.

What would have improved this further:

- Full written credit required explicitly identifying that some missing values were hidden inside character/string fields, explaining why a generic missing-value summary can miss them, and supporting the point with concrete evidence from the data.

---

## Task 3

Mark: `8/12`

What was done well:

- Your code for collapsing and relabelling the genres was fully successful.
- Your final grouped result had the required structure and level set.

What was partly correct:

- There was no partly-correct middle ground on this task.

What lost marks:

- Your written explanation did not earn credit because it did not make the weighted-average / masking issue clearly enough in the final awarded mark.

What would have improved this further:

- Full credit required the correct collapsing workflow, the required final grouped structure, and a clear written explanation of how combining broad genres can hide or dilute the underlying pattern, supported by numerical evidence.

---

## Task 4

Mark: `4/6`

What was done well:

- You correctly produced the grouped mean-rating table.
- You correctly presented the results in sorted table form.
- You correctly identified the top-rated genre and supported it with the required value.

What was partly correct:

- There was no partly-correct middle ground on this task.

What lost marks:

- The final written budget-comparison part did not earn credit in the awarded mark.

What would have improved this further:

- Full credit required naming the top-rated genre with its mean rating, then giving separate budget evidence for Horror, Action, and Sci-Fi, together with a clear explanation of the masking pattern.

---

## Task 5

Mark: `8/14`

What was done well:

- You correctly identified the top 10 films for the plot.
- You correctly ordered the film titles for the boxplot comparison.
- You correctly identified the film with the lowest individual rating.

What was partly correct:

- There was no partly-correct middle ground on this task.

What lost marks:

- You did not meet the required presentation / formatting part of the task.
- Your written explanation of the box sizes and IQRs did not earn credit in the final awarded mark.

What would have improved this further:

- Full written credit required a more specific explanation of what the box lengths represent and a clearer application of that idea to the films shown in your own plot.

---

## Task 6

Mark: `13/14`

What was done well:

- You correctly created the age-tier structure needed for the comparison.
- You correctly produced the overall 2D engagement comparison.
- You correctly produced the age-by-subscription 3D comparison.
- You clearly explained Simpson’s Paradox in this task.
- You clearly explained the confounding pattern, including how age and subscription type affect the result.

What was partly correct:

- There was no partly-correct middle ground on this task.

What lost marks:

- A small final deduction remained in the awarded mark after the final moderation pass, so this task did not receive full credit.

---

## Task 7

Mark: `5/6`

What was done well:

- You correctly tokenised the review text and prepared the word counts.
- You correctly produced the required comparison bar chart.
- Your written interpretation clearly explained the chosen words and what they suggest about genre, rating, or audience reaction.

What was partly correct:

- There was no partly-correct middle ground on this task.

What lost marks:

- A small final deduction remained in the awarded mark after the final moderation pass, so this task did not receive full credit.

---

## Task 8

Mark: `11/12`

What was done well:

- You correctly joined the Bing sentiment data and prepared the sentiment workflow.
- You correctly calculated the required sentiment summary.
- You correctly produced the comparison scatter plot.
- Your written explanation of the Horror result was detailed and well supported.

What was partly correct:

- There was no partly-correct middle ground on this task.

What lost marks:

- A small final deduction remained in the awarded mark after the final moderation pass, so this task did not receive full credit.

---

## Task 9

Mark: `10/12`

What was done well:

- You correctly built the main TF-IDF pipeline.
- You correctly explained why a common word such as “film” can receive a TF-IDF of zero.
- You clearly explained how IDF works and why common words are downweighted.

What was partly correct:

- The top-term extraction was only partly correct.

What lost marks:

- The deductions on this task came from the partly-correct points noted above, which were not complete enough for full credit.

What would have improved this further:

- Full credit required the complete TF-IDF workflow, exactly the top three terms per genre, a precise explanation of why a common word such as `film` can receive zero TF-IDF in the relevant genre, and a clearer explanation of the IDF mechanism with an explicit frequency-versus-weight comparison.

---

## Task 10

Mark: `7/8`

What was done well:

- Your recommendation was specific enough to earn credit.
- You supported the recommendation with strong task-linked evidence, including `3` valid citations.
- You included a relevant and specific limitation.

What was partly correct:

- Your final recommendation was read as: "convert younger Basic users to Premium through targeted Horror content and upgrade offers".

What lost marks:

- The recommendation was not judged coherent enough to receive credit for the overall argument.
- The main issue here was that the recommendation and the supporting evidence did not connect tightly enough into one fully consistent argument.

What would have improved this further:

- Full credit required a more concrete recommendation, more fully developed task-linked evidence, a tighter connection between the recommendation and the evidence, a clearly relevant limitation, and an answer within the word limit.

---

## Summary

- Stronger tasks in this coursework: Task 6, Task 7, Task 8.
- Tasks with the largest deductions: Task 1, Task 5, Task 3.


## Marking Process

- Final note on the marking process: this coursework was marked using an AI-assisted workflow under lecturer supervision. AI tools were used to support drafting and organisation within the marking process, but the marking criteria, quality checks, and final released feedback were overseen by the lecturer, with human review applied where needed.
