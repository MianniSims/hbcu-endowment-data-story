# HBCU Endowment Data Story

This project examines how endowment resources are distributed across 97 open Historically Black Colleges and Universities with reported endowment data. The analysis connects institutional endowment levels with student enrollment to show how financial resources vary across the HBCU sector.

[View the interactive Flourish story](https://public.flourish.studio/story/3801165/)

[![Preview of the HBCU Endowment Data Story](images/flourish_story_preview.png)](https://public.flourish.studio/story/3801165/)

## Project Overview

HBCUs serve more than 300,000 students represented in this dataset, but endowment resources are not evenly distributed across institutions. This project explores how many institutions operate below major endowment thresholds and how many students attend those institutions.

The visualization was created as a seven-part interactive story using Flourish.

## Key Findings

1. The dataset contains 97 open HBCUs with reported endowment information.

2. These institutions enroll a combined 300,522 students.

3. Only 13 institutions have endowments of at least $100 million.

4. The remaining 84 institutions represent approximately 87 percent of the HBCUs in the dataset.

5. Those 84 institutions educate 226,412 students, approximately 75 percent of the students represented in the analysis.

6. The median HBCU endowment in the dataset is approximately $16.7 million.

7. Nearly half of the institutions have endowments below $10 million.

8. Seven institutions have endowments below $1 million.

## Notable Comparison

North Carolina Agricultural and Technical State University enrolls 13,012 students and has an endowment of approximately $201.9 million.

St. Philip's College enrolls 12,653 students but has an endowment of approximately $0.5 million.

Although the institutions have similar enrollment levels, their available endowment resources differ substantially.

## Dataset

The dataset contains one row per institution and includes:

1. Institution name

2. City and state

3. Founding year and decade

4. Public or private classification

5. Endowment value

6. Student enrollment

7. Institution status

8. Endowment classification

9. Student enrollment classification

10. Geographic coordinates

11. Source information

The Excel dataset is available in the [`data`](data/) folder.

## Methodology

The analysis was limited to institutions classified as open and having reported endowment data. Endowment values were converted into numeric values measured in millions of dollars. Institutions were then classified according to endowment and enrollment ranges.

Summary statistics were calculated for the number of institutions, total enrollment, median endowment, and the number of students attending institutions above or below the $100 million threshold.

Additional details are available in [`methodology.md`](methodology.md).

## Tools

1. Microsoft Excel for data collection, cleaning, and classification

2. Flourish for interactive visualization and data storytelling

3. GitHub for documentation and project presentation

## Limitations

The dataset combines information from multiple publicly available sources. Reporting years and definitions may differ across institutions. Endowment values represent institutional financial resources but do not independently measure annual operating budgets, institutional effectiveness, or the resources available to individual students.

## Author

Mianni Sims

M.S. Applied Data Science and Analytics, Howard University
