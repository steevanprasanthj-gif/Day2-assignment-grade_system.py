# Student Grade Manager

name = input("Enter student name: ")
mark = int(input("Enter student mark: "))

if mark >= 90:
    grade = "A"
elif mark >= 80:
    grade = "B"
elif mark >= 70:
    grade = "C"
elif mark >= 60:
    grade = "D"
else:
    grade = "F"

print("\nStudent Name:", name)
print("Mark:", mark)
print("Grade:", grade)
