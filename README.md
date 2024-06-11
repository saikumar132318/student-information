# student-information

students = {
    1: {"name": "HARI", "age": 20, "grade": "A"},
    2: {"name": "SIDDESH", "age": 21, "grade": "B"},
    3: {"name": "BHANU", "age": 19, "grade": "C"},
    4: {"name": "KUMAR", "age": 22, "grade": "A"},
    5: {"name": "PRASHANTH", "age": 20, "grade": "B"}
}

roll_number = int(input("Enter roll number: "))

if roll_number in students:
    print("Roll Number:", roll_number)
    print("Name:", students[roll_number]["name"])
    print("Age:", students[roll_number]["age"])
    print("Grade:", students[roll_number]["grade"])
else:
    print("Student not found")
