Download Link: https://assignmentchef.com/product/solved-solvedcomputer-science-221-program-6
<br>
Learning objective:

To useinheritance.

Assignment:

Writea Java application that implements a small student grade system as definedbelow. Write the hierarchy so that all fields and methods are as high in thehierarchy as possible.

Definea class Course that has a department (String),a number (int), credit hours (int),and a grade (String or char). Don’t initialize the grade in the constructor.(The professor doesn’t know what grade you will make at the beginning of thecourse.) Each field should have a getter and a setter, and there is a toString()method.

Definea class Person. A Person has a first name, alast name, and ID number (int). Each field shouldhave a getter and a setter, and there is a toString() method.

Derivethe class Student from the class Person.A Student has a major and a list ofcourses (ArrayList&lt;Course). (Remember thatcourses are a component, not part of the inheritance hierarchy.) There is aclass variable that keeps track of the total number of students. There are twoconstructors, one without a major and one with; a setter that changes themajor, a method that adds a course to the course list, a method that changesthe grade of a course, and a method that computes the GPA of the courses in thelist. There is a toString() method that listsname, ID, major or “undeclared”, GPA, and if the student has a GPAless than 2.0, “On probation”. Use a grade points of A = 4, B = 3, C= 2, D = 1, F = 0. Do not use plus and minus grades. The GPA is sum of gradepoints divided by sum of hours.

Themethod find() locates a course within thestudent’s course list. It will have to search the ArrayList for a match ondepartment and a match on number. Itreturns the position that it finds. The method changeGrade() uses the position andcalls the Course’ssetGrade()to change the grade.

Theclass GraduateStudent, derived from the class Student,has a thesis topic. There are one constructor with a major, and a setter thatchanges the thesis topic. There is a toString() method that listsname, ID, major , GPA, and if the student has a GPA less than 3.0, “Onprobation”. It also lists the thesis topic or “none”.

Writea class Test.java that has no input. In Test.javaadd some students and graduate students with majors and some without. Addmajors to some without, and leave some majorless. Add courses to all students.Then add grades to the courses. Make an ArrayList and GraduateStudent and put all students andgraduate students into it. Print the information as described above on all Studentsand GraduateStudents. Then print the total number ofstudents from the class variable.

Allclass names and method signatures should be exactly as specified. Thus I shouldbe able to substitute my test program for yours, and everything should workperfectly.

Constructor and Method Signatures (except for simplegetters and setters):

publicCourse ( String dept, int number, int hours )…

publicPerson ( int ID, String first, String last )…

publicStudent( int ID, String first, String last )…

publicStudent( int ID, String first, String last, String major )…

publicvoid addCourse( String dept, int num, int hours )…

publicvoid changeGrade ( String dept, int num, char grade )…

publicGraduateStudent( int ID, String first, String last, String major )…

Submission instructions:

Upload the files Course.java, Person.java, Student.java, GraduateStudent.java, and Test.java to “Program 6”.Do not submit class files or any of the BlueJ control files. Be sure to pressthe submit button.

Policies:

The policies given on WebCT are in effectfor this and all assignments.

You may submit on WebCT multiple times, sothere is no excuse for not submitting partial solutions.