#---------------------------------------Task 1.py-------------------------
student_name=input("Enter a Student Name: ")
student_marks={'Rohan':78,'sohan':98,'mohan':78}
if student_name in student_marks:
    print(f"{student_name}'s marks: {student_marks[student_name]}")
else:
    print("student not found in record")


#---------------------------------------Task 2.py-------------------------

list=[1,2,3,4,5,6,7,8,9,10]
print("original list:",list)
my_list=list[:5]
print("Extracted First Five Element: ",my_list)
my_list.reverse()
print("Reversed Extracted Element: ",my_list)

