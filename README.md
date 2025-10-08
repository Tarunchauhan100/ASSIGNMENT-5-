# ASSIGNMENT-5-
# Module 6: Data Structures and Strings in Python
# Task 1 
 Step 1: Create a dictionary with student names and their marks
 Step 2: Ask the user to input a student's name
 Step 3: Retrieve and display the corresponding marks
 Step 4: If the student’s name is not found, display a message
 # Code
 students = {
    "amit": 85,
    "neha": 92,
    "rohit": 76,
    "priya": 89,
    "tarun": 95
}
name = input("Enter the student's name: ")
if name in students:
  print(name,"'s marks:", students[name])
else:
    print("Student not Found.")

# Output 
Enter the student's name:  tarun
tarun 's marks: 95

Enter the student's name:  mdjd
Student not Found.


# Task 2 
 Step 1: Create a list of numbers from 1 to 10
 Step 2: Extract the first five elements
 Step 3: Reverse these extracted elements
 Step 4: Print both the extracted list and the reversed list
# Code
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
first_five = numbers[:5]
reversed_list = first_five[::-1]
print("Original List : ",numbers)
print("Extracted First five elements:", first_five)
print("Reversed List:", reversed_list)

# OutPut
Original List :  [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Extracted First five elements: [1, 2, 3, 4, 5]
Reversed List: [5, 4, 3, 2, 1]
