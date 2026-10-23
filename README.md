# Medical Appointment No-Show Analysis

## Project overview
This beginner data analytics project explores appointment attendance patterns using a synthetic medical appointment dataset. The goal is to practice cleaning data, calculating no-show rates, and comparing appointment groups.

## Questions explored
- What percentage of appointments were missed?
- How did observed no-show rates differ between appointments with and without an SMS reminder?
- How did rates differ by gender?

## Tools
- Python
- pandas
- Seaborn
- Matplotlib
- Excel

## Data
The workbook contains generated practice records, not real patient or clinic data. It includes a few intentional issues—duplicate rows, unusual ages, and a negative wait period—for cleaning practice.

## Project steps
1. Load the Excel workbook into pandas.
2. Inspect row counts, missing values, duplicates, ages, and appointment dates.
3. Clean duplicate and invalid records.
4. Create a numeric no-show flag (`1` = missed, `0` = attended).
5. Calculate overall and group-level no-show rates.
6. Visualize the SMS comparison.

## Run the notebook
Install the required packages:

```bash
python -m pip install pandas seaborn matplotlib openpyxl
