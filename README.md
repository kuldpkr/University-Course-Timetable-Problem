# University-Course-Timetabling-Problem
A project done as a part of the course IME639A

1) File dim.txt
	It contains the dimensions of the problem.
	First line contains the number of Classes(C).
	2nd line contains the number of teachers(T).
	3rd line contains number of rooms(R).
	4th line contains number of days per week(D).
	5th line contains number of periods per day(P).
--------------------------------------------------------------------------------------------------------
2) File matrix.txt
First C rows of the file indicate the number of times each class-teacher pair is to meet each other in room 1 across P periods. 
The next C rows indicate the number of times each class-teacher pair is to meet each other in room 2 across P periods and so on.

--------------------------------------------------------------------------------------------------------
3) File output.txt
This file has a matrix of the dimension R * slots where slots = D * P.
The lth row and kth column stores two integers {i, j}, which means during kth slot in the lth room jth teacher teaches ith class.
