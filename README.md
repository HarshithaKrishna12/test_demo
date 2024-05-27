The program consists of two main functions: get_student_data() and determine_pass_fail()


get_student_data() Function:

This function collects data about students from the user.
It first prompts the user to enter the number of students.
For each student, it asks the user to input the student's name and grade.
Finally, it returns the dictionary containing all the student data.

determine_pass_fail(students, pass_mark=3.5) Function:

This function takes a dictionary of students (with their grades) and an optional passing mark default is 3.5.
It iterates over each student in the dictionary.
For each student, it checks if the grade is greater than or equal to the passing mark.
It prints "Pass" if the student meets the passing mark, otherwise it prints "fail".

Main Program:

The main program first calls the get_student_data() function to collect student data.
It prints the dictionary of students and their grades.
Then, it calls the determine_pass_fail(students) function to print pass/fail results for each student.
