Certainly! Here's an example of Python 2 code that calculates the total and average marks for a student, as well as their corresponding grade based on the average:

```python
subject1 = float(raw_input("Enter marks for Subject 1: "))
subject2 = float(raw_input("Enter marks for Subject 2: "))
subject3 = float(raw_input("Enter marks for Subject 3: "))

total_marks = subject1 + subject2 + subject3
average_marks = total_marks / 3

print("Total Marks: " + str(total_marks))
print("Average Marks: " + str(average_marks))

if average_marks >= 90:
    grade = "A"
elif average_marks >= 80:
    grade = "B"
elif average_marks >= 70:
    grade = "C"
elif average_marks >= 60:
    grade = "D"
else:
    grade = "F"

print("Grade: " + grade)
```

In this code, the user is prompted to enter the marks for three subjects. The total marks are calculated by summing up the individual subject marks, and the average marks are calculated by dividing the total marks by 3. Finally, based on the average marks, the corresponding grade is determined and displayed.

Please note that Python 2 reached its end-of-life status on January 1, 2020, and it is recommended to use Python 3 for new projects as it is actively maintained and receives regular updates.
