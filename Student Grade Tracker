# Project 1: Smart student grade tracker
# Created by: Aditya Rathore

print("=== Welcome to the Smart student grade tracker ===")

# 1. Ask for student details
student_name = input("Enter Student Name: ")
num_subjects = int(input("How many subjects do you want to calculate? "))

# 2. Initialize variables
total_marks = 0

# 3. Use a loop to collect marks for each subject
for i in range(1, num_subjects + 1):
    marks = float(input(f"Enter normalized marks for Subject {i} (out of 100): "))
    total_marks += marks

# 4. Calculate the average percentage
percentage = total_marks / num_subjects

# 5. Determine the GPA and Status based on the percentage
if percentage >= 90:
    gpa = 4.0
    status = "Outstanding (Pass)"
elif percentage >= 80:
    gpa = 3.5
    status = "Excellent (Pass)"
elif percentage >= 70:
    gpa = 3.0
    status = "Good (Pass)"
elif percentage >= 50:
    gpa = 2.0
    status = "Average (Pass)"
else:
    gpa = 0.0
    status = "Fail (Needs Improvement)"

# 6. Display the final scorecard report
print("\n================ REPORT CARD ================")
print(f"Student Name      : {student_name}")
print(f"Total Marks Scored: {total_marks} out of {num_subjects * 100}")
print(f"Final Percentage  : {percentage:.2f}%")
print(f"Estimated US GPA  : {gpa}")
print(f"Academic Status   : {status}")
print("============================================")