---
title: On the Effects of Active Learning Environments in Computing Education
subtitle: Tyler Greer, Qiang Hao, Mengguo Jing, Bradley Barnes
author: Zayd Mohammed and David Rambo
date: November 6, 2026
---

# The Authors' Aim

- Prior research has shown that active learning classrooms have positive effects on learning outcomes.

::: incremental

- This paper tries to replicate that research while better accounting for potentially confounding factors.

:::

# Active Learning Classroom

::: incremental

- Its design _assumes_ that lecture halls are not best suited to active learning.
- It features "movable chairs, round tables, typically multimedia equipments to decentralize the role of the instructors and encourange peer communications" (Greer, et al. 267).
- They are expensive to build or to retrofit lecture halls ($100k to upgrade a 30-seat classroom).
- They fit many fewer students.

:::

# Active Learning Techniques

Includes:

::: incremental

- "team-based learning, paired-programming and peer instruction" (Greer, et al. 268).
- Group activities, like solve a problem, often on a whiteboard or with a computer display.
- Act out sorting algorithm using numbers written on pieces of paper.\
  \
  Hossein Hakimzadeh, Raman Adaikkalavan, and Robert Batzinger. 2011. Successful implementation of an active learning laboratory in computer science. In Proceedings of the 39th annual ACM SIGUCCS conference on User services (SIGUCCS '11).

<!-- Find minimum number of ten numbers, each of which is written on its own piece of paper. Students have another blank paper, which can store one number. Viewing one number at a time and the scratch pad, find the minimum number. Then return to solo seating and code it in a high-level language. -->

:::

# Peer Instruction

<!-- The study we read used peer instruction as its exemplar for active learning. -->

::: incremental

- Catherine H Crouch and Eric Mazur. Peer instruction: Ten years of experience
  and results. American journal of physics, 69(9):970–977, 2001: <!-- at MIT -->
  - Students read and do practice problems ahead of class.
  - Class is divided into several chunks, each of which goes through the following sequence:
    1. Instructor gives a short presentation, concluding with a conceptual question ("clicker questions" i.e. polls).
    2. Students take a minute or two alone to formulate an answer.
    3. Students form groups and try to convince their peers of their answer.

:::

# Back to the study...

# Replication Motivation

Two limits to prior studies:

::: incremental

1. "lack of control of confounding factors," namely the "influence of learning pedagogies" (268)
2. "lack of control of false positives" b/c "significance levels were not properly corrected" when comparing "multiple factors between two groups" (268)

:::

# Study Design

::: incremental

- Grouped students into three sections, comparing classroom design and pedagogical style:

1. conventional = conventional classroom + lecturing
2. active = active learning classroom + active learning and teaching
3. hybrid = active learning and teaching in a conventional classroom

- Same instructor for all three.
- Collected data on major, gender, and age.
- Same two midterms and final exam.

:::

# Statistical Results

The researchers have implemented MANCOVA to examine the exam performance while taking demographic factors into account.

| Factor             | p-value | Significant? |
| ------------------ | ------: | ------------ |
| Pedagogical Method |   0.006 | Yes          |
| Classroom Type     |   0.042 | No\*         |
| Age                |   0.061 | No           |
| Gender             |   0.064 | No           |
| Major              |   0.923 | No           |

_The Bonferroni-adjusted significance threshold is p < 0.016._

::: incremental

- The teaching method was shown to be statistically significant.
- The classroom type was not shown to be significant after correction.
- The demographic factors were not significant predictors in this analysis.

:::

# Interpretation and Limitations

## Interpretation

::: incremental

- The pedagogical method mattered more in the reported statistical analysis.
- The findings show the importance of peer instruction.
- An expensive active learning classroom was not necessary for having improved outcomes.

:::

## Limitations

::: incremental

- This study was conducted in one introductory programming course.
- There was only one instructor and three course sections in this study.
- There were no active learning classrooms with traditional lectures.
- The results may not generalize to all of the institutions or courses.

:::

# Conclusions

## Main Takeaways

::: incremental

- Peer instruction has shown a statistically significant association with the exam performance.
- The classroom design alone did not show a statistically significant effect after correction.
- Universities should consider the role of these different teaching practices, not just the classroom infrastructure.

:::
