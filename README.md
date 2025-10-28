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

1. **Write a C++ program** (`predict.cpp`) that:
   - Reads the input CSV (`train.csv`)
   - Analyzes each row to infer the underlying pattern
   - Predicts the next 3 days of temperature for each row
   - Outputs predictions to a new file, `submission.csv`

2. **Submission format:**
   - `submission.csv` should have the same number of rows as the input
   - Each row should contain **3 predicted temperature values**, separated by commas

   Example:

   ```csv
   21.43,22.11,23.00
   18.92,19.07,18.85
   ...

---

## The Highest Score Gets a High Five :)

