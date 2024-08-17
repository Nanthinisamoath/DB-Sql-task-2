# sql_task2

Design DB model for Guvi Zen class

CREATE TABLE STUDENTS
(STUDENT TEXT);

INSERT INTO
STUDENTS(STUDENT)
VALUES(1),(2),(3);

CREATE TABLE ZEN_CLASS
( DAY INTEGER, TOPIC TEXT, TASK TEXT,RECORDED_LINK TEXT);

ALTER TABLE ZEN_CLASS 
ADD MENTOR TEXT 
DEFAULT "Ragav Kumar";

INSERT INTO 
ZEN_CLASS (DAY,TOPIC,TASK,RECORDED_LINK)
VALUES
(1,"Introduction to Browser & web","Introduction to Browser & web","Yes"),
(2,"Request & Response cycle","Request & Response cycle","Yes"), 
(3,"JS array & objects","Looping Of Arrays & Objects","Yes"), 
(4,"What is XMLHTTP Request? & scope","XMLHTTP Request","Yes"), 
(5,"Functions","IIFE & Annoymous Function","Yes"), 
(6,"Functions recap","Functions","Yes"), 
(7,"ES5 vs ES6","NIL","Yes"), 
(8,"OOP","OOP PROBLEMS","Yes"), 
(9,"MRF Array Method","MRF Method","Yes"), 
(10,"Complete Recap","NIL","Yes"), 
(11,"HTML","HTML & CSS Mini Task","Yes"), 
(12,"HTML recap CSS","NIL","Yes"), 
(13,"CSS","NIL","Yes"), 
(14,"CSS","NIL","Yes"), 
(15,"Responsive web design","NIL","Yes"), 
(16,"Bootstrap design demo","Responsive Design","Yes"), 
(17,"DOM","NIL","Yes"), 
(18,"Document vs Window","NIL","Yes"), 
(19,"Recap of Topics","CALCULATOR HTMLForms PAGINATION","Yes"), 
(20,"Recap of Topics","NIL","Yes"), 
(21,"Callback","Callback Hell","Yes"), 
(22,"Promise","NIL","Yes"), 
(23,"Fetch Api","NIL","Yes"), 
(24,"Promise_fetch - request info & request init","NIL","Yes"), 
(25,"Recap of Topics","3 API TASKS","Yes"), 
(26,"REACT","Pricing Table","Yes"), 
(27,"React hooks & states","Shop-Homepage","Yes"), 
(28,"React components","Dashboard","Yes"), 
(29,"React router","CRUD_Userlist","Yes"), 
(30,"recap with previous day topics","NIL","Yes"), 
(31,"Context API","API task completion using context","Yes"), 
(32,"recap with previous day topics","NIL","Yes"), 
(33,"AXIOS","CRUD using Axios","Yes"), 
(34,"formik in react","CRUD for product with validation","Yes"), 
(35,"practice with formik & recap","NIL","Yes"), 
(36,"Database - MySQL","MYSQL queries","Yes"), 
(37,"Database - MySQL","Design DB model for Guvi Zen class","Yes"), 
(38,"Database - MongoDB","MongoDB queries","Yes"), 
(39,"MongoDB","database-design-zen-class","Yes"), 
(40,"Nodejs","Nodejs file system","Yes"), 
(41,"Nodejs & Expressjs","Hall Booking Application","Yes"), 
(42,"Node & mongo DB connectivity","Mentor and Student Assigning with Database","Yes"), 
(43,"Nodejs deployment","Mentor and Student Assigning with Database","Yes"), (44,"Authentication","Password Reset Flow","Yes"), 
(45,"JWT","URL Shortener Application","Yes");

CREATE TABLE TASKS
(_STUDENT_ID INTEGER,NO_OF_DAYS INTEGER,TASK_COMPLETION TEXT);

INSERT INTO TASKS
(_STUDENT_ID,NO_OF_DAYS,TASK_COMPLETION)
VALUES
(1,1,"Yes"),
(1,2,"Yes"),
(1,3,"NO"),
(1,4,"Yes"),
(1,5,"Yes"),
(1,5,"Yes"),
(1,6,"Yes"),
(1,7,"NIL"),
(1,8,"Yes"),
(1,9,"Yes"),
(1,10,"NIL"),
(1,11,"Yes"),
(1,12,"NIL"),
(1,13,"NIL"),
(1,14,"NIL"),
(1,15,"NIL"),
(1,16,"Yes"),
(1,17,"NIL"),
(1,18,"NIL"),
(1,19,"Yes"),
(1,20,"NIL"),
(1,21,"Yes"),
(1,22,"NIL"),
(1,23,"NIL"),
(1,24,"NIL"),
(1,25,"Yes"),
(1,26,"NO"),
(1,27,"Yes"),
(1,28,"Yes"),
(1,29,"Yes"),
(1,30,"NIL"),
(1,31,"Yes"),
(1,32,"NIL"),
(1,33,"Yes"),
(1,34,"Yes"),
(1,35,"NIL"),
(1,36,"Yes"),
(1,37,"Yes"),
(1,38,"Yes"),
(1,39,"Yes"),
(1,40,"Yes"),
(1,41,"Yes"),
(1,42,"Yes"),
(1,43,"Yes"),
(1,44,"Yes"),
(1,45,"Yes"),
(2,1,"Yes"),
(2,2,"Yes"),
(2,3,"NO"),
(2,4,"Yes"),
(2,5,"Yes"),
(2,5,"Yes"),
(2,6,"Yes"),
(2,7,"NIL"),
(2,8,"Yes"),
(2,9,"Yes"),
(2,10,"NIL"),
(2,11,"Yes"),
(2,12,"NIL"),
(2,13,"NIL"),
(2,14,"NIL"),
(2,15,"NIL"),
(2,16,"Yes"),
(2,17,"NIL"),
(2,18,"NIL"),
(2,19,"Yes"),
(2,20,"NIL"),
(2,21,"Yes"),
(2,22,"NIL"),
(2,23,"NIL"),
(2,24,"NIL"),
(2,25,"Yes"),
(2,26,"NO"),
(2,27,"Yes"),
(2,28,"Yes"),
(2,29,"Yes"),
(2,30,"NIL"),
(2,31,"NO"),
(2,32,"NIL"),
(2,33,"Yes"),
(2,34,"Yes"),
(2,35,"NIL"),
(2,36,"NO"),
(2,37,"Yes"),
(2,38,"NO"),
(2,39,"Yes"),
(2,40,"Yes"),
(2,41,"NO"),
(2,42,"Yes"),
(2,43,"Yes"),
(2,44,"Yes"),
(2,45,"Yes"),
(3,1,"Yes"),
(3,2,"Yes"),
(3,3,"NO"),
(3,4,"Yes"),
(3,5,"Yes"),
(3,5,"Yes"),
(3,6,"Yes"),
(3,7,"NIL"),
(3,8,"Yes"),
(3,9,"Yes"),
(3,10,"NIL"),
(3,11,"Yes"),
(3,12,"NIL"),
(3,13,"NIL"),
(3,14,"NIL"),
(3,15,"NIL"),
(3,16,"Yes"),
(3,17,"NIL"),
(3,18,"NIL"),
(3,19,"Yes"),
(3,20,"NIL"),
(3,21,"Yes"),
(3,22,"NIL"),
(3,23,"NIL"),
(3,24,"NIL"),
(3,25,"NO"),
(3,26,"NO"),
(3,27,"Yes"),
(3,28,"Yes"),
(3,29,"Yes"),
(3,30,"NIL"),
(3,31,"Yes"),
(3,32,"NIL"),
(3,33,"Yes"),
(3,34,"Yes"),
(3,35,"NIL"),
(3,36,"Yes"),
(3,37,"Yes"),
(3,38,"Yes"),
(3,39,"Yes"),
(3,40,"Yes"),
(3,41,"Yes"),
(3,42,"NO"),
(3,43,"NO"),
(3,44,"NO"),
(3,45,"NO");



<img src="task6img.png" alt=""/>
<img src="task7img.png" alt=""/>
<img src="task8img.png" alt=""/>
SELECT * FROM STUDENTS JOIN ZEN_CLASS;

<img src="task9img.png" alt=""/>
<img src="task10img.png" alt=""/>
<img src="task11img.png" alt=""/>

SELECT STUDENT,TASK,TASK_COMPLETION FROM STUDENTS  JOIN TASKS ON STUDENT = _STUDENT_ID JOIN ZEN_CLASS ON DAY=NO_OF_DAYS WHERE STUDENT = 3;