# Attendance Grading

- Step 1: Input the proper session length into the session_length variable
- Step 2: Input the csv name into the csv_name variable
- Step 3: Input the assignment name from the gradebook into the assignment_name variable
- Step 4: Make sure the zoom recording csv has records occuring after the due date removed before running results (not yet fixed).

Results are retrieved in two csv's "Testing.csv" and "grading_results.csv". The first csv "Testing.csv" returns with more columns joined to the gradebook "Name", "View Duration (minutes)" and "Grade" to verify that the grading script is placing the correct grades in the correct student's row. "Testing.csv" is for debugging/testing purposes not to be put on Canvas.

## CSV's used for testing/debugging purposes

- Preliminary.csv
- Testing.csv
- grade_count.csv

## CSV's required for script to function

- Gradebook csv (gradebook_name)
- Zoom recording csv (csv_name)

## Other necessary inputs

- Zoom session length (session_length)
- Name of assignment in gradebook (assignment_name)

Final results are placed in the "grading_results.csv" use that for inputting into canvas.

TODO: Removing columns from the zoom recording csv where attendance is inadmissible for credit (too late) automatically rather than having to manually remove them.
