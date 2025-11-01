# Cornell Autonomous Motions — Onboarding Assignment

Welcome to the **Cornell Autonomous Motions (CAM)** onboarding challenge!
This task is designed to get you comfortable with C++ programming.

---

## Overview

You are provided with a **CSV file** containing temperature data:

- Each **row** represents a different independent dataset (e.g., a location).
- Each **column** represents **consecutive days** of temperature measurements, **10 days** of data per row.

Your goal is to **predict the next 3 days of temperature values** for each row using a **C++ program**.

The data follows an **underlying periodic trend** with some added zero-mean noise.

---

## Task

### 1. Write a C++ program (`predict.cpp`) that

- Reads the input CSV (`train.csv`)
- Analyzes each row to infer the underlying pattern
- Predicts the next 3 days of temperature for each row
- Outputs predictions to a new file, `submission.csv`

### 2. Submission Format

For Kaggle-style evaluation, your `submission.csv` must have:

1. **Columns:**

- `id` — unique integer for each row (matching the id in train.csv or solution.csv)
- `day_1, day_2, day_3` — predicted temperature values for the next 3 days

2. **Number of rows:** Same as the number of rows in train.csv.

3. **Example:**

```text
id,day_1,day_2,day_3
1,21.43,22.11,23.00
2,18.92,19.07,18.85
3,25.10,25.35,25.50
...
```

4. **Notes:**

- The `id` must match the `id` column in the solution CSV (`solution.csv`) for correct scoring.
- All predicted values must be numeric.

This ensures your submission can be directly evaluated by Kaggle's automatic scoring system using the **Mean Absolute Error (MAE)** metric.

### 3. The Highest Score Gets a High Five :)
