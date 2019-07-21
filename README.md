
## Objective: Build 2 sets of CRUD routes for 2 models, Students and Tests

### Details

	- For now, our models/ database should just be objects. Make a file called student.js and declare an array of objects with some students.
	-Make Sure you require test.js in your main file. 
	-run your server and send requests to it with your browser and postman. 

	Example:

    Student: [{id :1, name : 'John'},{id:2, name:Jim},{id:3,name:Jane}]

Part 1: 

 Necessary routes:

		- Get all students
		- Add Student
		- Update student name
		- Delete Student


Part 2
Example:
		Test [{id : 1, score: 99, subject : 'Physics', studentID : 2},{id:2, score:87,subject:'Physics',studentId:1}, {id:3,score, subject:"{Physics}}]

Add other tests via your routes, make sure all are working

Neccessary routes:
		- Get all test scores
			- Update test score
			- Get top scoring student, should return the student's name. 
			- Get mean test score 
			- Delete Score
			- Add Score


### How to test routes without a frontend or specs
- GET: use your browser
- POST / PUT / DELETE :
 - [Postman](https://www.getpostman.com/)
