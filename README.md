# Data-structure-practical-program-13
# Program to store student marks using array (list)

n = int(input("Enter number of students: "))

marks = []

# Input marks
for i in range(n):
    mark = int(input("Enter mark of student " + str(i+1) + ": "))
    marks.append(mark)

# Display marks
print("Student Marks are:")
for i in range(n):
    print("Student", i+1, ":", marks[i])

# Calculate total and average
total = sum(marks)
average = total / n

print("Total Marks =", total)
print("Average Marks =", average)
Enter number of students: 3
Enter mark of student 1: 80
Enter mark of student 2: 75
Enter mark of student 3: 90

Student Marks are:
Student 1 : 80
Student 2 : 75
Student 3 : 90
Total Marks = 245
Average Marks = 81.67
