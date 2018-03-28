# This is Below Average Preschool Report Cards

After years of working in the sanitation department of This is Below Average Preschool (TIBAP), you have finally achieved your life long dream of working as the assistant to the assistant of the assistant principal of TIBAP. As the assistant to the assistant of the assistant, your first job is to make sure scores are sent out in a timely manner.  

Last week, you sent out an email requesting that teachers fill out a form for all their students in the following format:

| Student ID  | Subject | Grade (%) | Teacher ID |
|---|---|---|---|


Unfortunately and to no one's surprise, the teachers at TIBAP are, well, below average and thus cannot follow simple instructions.  So what you have received back is data that is incomplete or not in the desired format. 

Now with the assistant to the assistant principal breathing down your neck, you have no choice but to fix the data yourself and make sure the report cards get sent out on time.  


## Your Assignment
You must take the data in `grades.csv` it into an output file.

The file will be a `csv` that contains a single row for each student with the following columns.
|Student ID| Grade Subject<sub> 1<sub>|Grade Subject<sub> ...<sub>|Grade Subject <sub>k<sub>|Overall Grade| Awards |Teacher ID|
|---|---|---|---|---|---|---|

### Things to Know:
Grade averages will need to be outputted in the numerical format [0-100] (%)
Teachers have inputed grades in one of three forms
1. [0-100]%
2.  A letter grade {A, B, C, D, F} 
3. Just blank spaces - it could be a single blank space or it could be many

In the first case you can take the number as-is. In the second assume that an A = 90%, a B = 80%, a C=70%, a D=60%, and a F = 50% (For simplicity you can assume that there are no +/- grades i.e. A+, B-, etc.) Finally, in the third case a blank grade is considered to be a 0%.

The subjects will be the following: 
1. Nap-Time
2. Play-Time
3. Potty-Time
4. Manners
5. Quantum Mechanics

Every student will have a grade in one of the three forms foreach subject. The Overall Grade will be calculated by taking the average of his/her grades across the 5 subjects. 

The award category is meant to recognize student with any special achievements this year and currently the Principal is serving two awards: Star Student and Stupid Student. If a student has an overall grade of 90% or better he/she is a star. Similarly, if the student has an overall grade of 50% or worse he/she is stupid. In your output file you will mark those awards with the text string "star" or "stupid" respectively.

You can assume that every student ID will start with an S and will be followed by 8 numbers (i.e. S12345678).
You can assume that every Teacher ID will start with an T and will be followed by 4 numbers (i.e. S1234).

## Resource and Tips
[Code Academy](https://www.codecademy.com/learn/learn-python) - for basic python syntax and tips


