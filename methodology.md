# Methodology

## Research Question

How are endowment resources distributed across open HBCUs, and what proportion of students attend institutions with endowments below $100 million?

## Data Collection

The dataset contains 97 open Historically Black Colleges and Universities with reported endowment information. Institution-level information was compiled from publicly available sources. A source link is included for each institution in the dataset.

## Data Preparation

The following preparation steps were used:

1. Institution names, locations, founding years, institution types, enrollment figures, and endowment values were collected.

2. Institutions were classified as open or closed.

3. The analysis was limited to open institutions with reported endowment data.

4. Endowment values originally displayed using millions or billions were converted into numeric dollar values.

5. Enrollment values were stored as numeric student counts.

6. Endowment classifications were created to group institutions into comparable financial categories.

7. Enrollment classifications were created to compare institutions of different sizes.

8. Latitude and longitude fields were included to support geographic visualization.

## Calculated Fields

### Numeric Endowment

Endowment amounts were standardized into numeric values. For example, an endowment reported as $1.032 billion was converted to $1,032 million and $1,032,000,000.

### Endowment Threshold

Institutions were divided into two groups:

1. Endowment of at least $100 million

2. Endowment below $100 million

### Enrollment Classification

Institutions were grouped by student enrollment, including institutions with fewer than 1,000 students, 1,000 to 4,999 students, 5,000 to 9,999 students, and at least 10,000 students.

## Summary Measures

The analysis calculated:

1. Number of open HBCUs with reported endowment data

2. Combined student enrollment

3. Median institutional endowment

4. Number and percentage of institutions below $100 million

5. Number and percentage of students attending institutions below $100 million

6. Number of institutions below $10 million and $1 million

## Visualization

The cleaned data was imported into Flourish and presented as a seven-part interactive story. Bubble size, position, grouping, and color were used to reveal changes in endowment and enrollment patterns across institutions.

## Limitations

The information was collected from multiple sources that may use different reporting years and definitions. Endowment amounts can change over time and should be interpreted as a snapshot rather than current real-time financial information.

Institutional endowment is also not equivalent to an annual operating budget. A larger endowment does not mean that the entire amount is available for immediate spending because portions may be restricted by donors or institutional policies.
