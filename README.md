# Attendance Grading

- Step 1: Download an updated version of the gradebook
- Step 2: Input the proper session length into the session_length variable
- Step 3: Input the csv names into the respective variables
- Step 4: Input the assignment name from the gradebook into the assignment_name variable
- Step 5: Make sure the zoom recording csv has records occuring after the due date removed before running results.

Results are retrieved in "grading_results.csv". The remaining csv's are used for debugging purposes. "Testing.csv" returns with more columns joined to the gradebook: "Name", "Duration (minutes)" "View Duration (minutes)", "Total View Time (minutes) and "Grade" to verify that the grading script is placing the correct grades in the correct student's row. "Testing.csv" is for debugging/testing purposes not to be put on Canvas.

## CSV's used for testing/debugging purposes

- Preliminary.csv
- Testing.csv
- grade_count.csv
- live_and_recording.csv
- grade_verification.csv

## CSV's required for script to function

- Gradebook csv (gradebook_name)
- Zoom recording csv (recording_csv_name)
- Zoom live csv (live_csv_name)

## Other necessary inputs

- Zoom session length (session_length)
- Name of assignment in gradebook (assignment_name)

Final results are placed in the "grading_results.csv" use that for inputting into canvas.

TODO: Removing columns from the zoom recording csv where attendance is inadmissible for credit (student watched too late) automatically rather than having to manually remove them.
