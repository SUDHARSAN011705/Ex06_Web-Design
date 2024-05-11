# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```

## OUTPUT
![326531127-83afeb37-e02a-4c57-806b-6e35b9813258](https://github.com/SUDHARSAN011705/Ex06_Web-Design/assets/167398236/be1797ef-3434-4c7a-ba17-cda54cf4bf4d)

![326531171-0515fa7f-ae3c-4f32-a2f6-e38f5e597e21](https://github.com/SUDHARSAN011705/Ex06_Web-Design/assets/167398236/1cdaca50-f81c-49a0-99e5-536a2e9adf74)

![326531205-f3347c8f-14ec-4082-ac02-4edb320fa492](https://github.com/SUDHARSAN011705/Ex06_Web-Design/assets/167398236/6ef55cf8-6cd5-436e-bab2-e63f309de4d8)

![326531237-c1607114-8956-4d38-973a-7b915be476f4](https://github.com/SUDHARSAN011705/Ex06_Web-Design/assets/167398236/1f9f94f5-e0b2-4bd3-973c-753a9cf602b5)

![326531425-b7e0fa7f-773c-42f3-8cd1-b76abd9e4a62](https://github.com/SUDHARSAN011705/Ex06_Web-Design/assets/167398236/1afe1596-b411-429a-af53-bfb9dbdca479)

![326531452-cfc0f5b3-6a0b-4e2f-9142-e2c2fc30332b](https://github.com/SUDHARSAN011705/Ex06_Web-Design/assets/167398236/cfe18a62-babb-44b5-873a-cebcc204561f)

## RESULT
  Student result using JavaScript is created successfully.
