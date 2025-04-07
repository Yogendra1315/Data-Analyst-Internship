## Netflix Dataset Cleaning Summary

**Steps Performed:**

1. Renamed columns to uppercase with underscores.
2. Filled missing values:
   - DIRECTOR → 'UNKNOWN'
   - CAST → 'NOT AVAILABLE'
   - COUNTRY → 'UNKNOWN'
   - RATING → 'NOT RATED'
   - DURATION → 'UNKNOWN'
3. Removed duplicate rows (if any).
4. Converted DATE_ADDED to datetime format.
5. Stripped extra whitespace in text columns.

**Final Rows:** [insert final row count]  
**Final Columns:** 12

Data is now cleaned and ready for analysis.
