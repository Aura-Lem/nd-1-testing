TS 1. Create ToDo
TS 2. Edit ToDo
TS 3. Delete Todo
TS 4. Changing the status of a task
TS 5. ToDo filter
TS 6. Matching UI elements


TC 1.1. Positive create ToDo
Steps:
1. Open app page: https://todolist.james.am/
2. Input todo name: [darbu sarasas, 265568456, !&%$$^&&&%$, DARBU SARASAS, Lorem50]
3. Press key [Enter]
4. Observe result

Expected result: Add task.
Actual result:

Status: PASS

Comments:

TC 1.2. Negative create ToDo with spaces
Steps:
1. Input todo with spaces: [___darbu sarasas, darbu sarasas___, ___darbu sarasas___]
2. Press key [Enter]
3. Observe result

Expected result: Creates a task without spaces.
Actual result:

Status: PASS

Comments:

TC 2.1. Positive edit ToDo
Steps:
1. Double-cklick on task
2. Change task
3. Press key [Enter]
4. Observe result

Expected result: Change task.
Actual result:

Status: PASS

Comments:

TC 3.1. Positive delete ToDo
Steps:
1. Press icon delete task (x)
2. Observe result

Expected result: Delete task.
Actual result:

Status: PASS

Comments:

TC 4.1. Positive Mark as completed ToDo
Steps:
1. Click check box
2. Observe result

Expected result: Put a check mark in the box and crossed out the task.
Actual result:

Status: PASS

Comments:

TC 4.2. Positive Mark as completed all ToDo
Steps:
1. Press the button to select all tasks
2. Observe result

Expected result: Mark all tasks and crossed out them.
Actual result:

Status: PASS

Comments:

TC 4.3. Positive Mark all active ToDo
Steps:
1. Press the button to uncheckt all tasks
2. Observe result

Expected result: All tasks will be active again.
Actual result: The button must be pressed twice to activate.

Status: FAIL

Comments:

TC 5.1. Positive Visual filter
Steps:
1. Press button: [Completed, Active, Clear All]
2. Observe result

Expected result: Must show [Completed tasks, Active tasks, Clear all completed tasks].
Actual result: 

Status: PASS

Comments:

TC 6.1. Positive Check responsive design
Steps:
1. Test the mobile version and on different screen widths
2. Observe result

Expected result: All app elements adapt to the screen size.
Actual result: From 444px the title overlaps.

Status: FAIL

Comments:

TC 6.2. Positive All text
Steps:
1. Check that all texts are grammatically correct
2. Observe result

Expected result: All texts are written grammatically correct.
Actual result: Button "Active" name starts with a lowercase letter. The note about editing tasks is misspelled.

Status: FAIL

Comments: