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
<head>
<title>JavaScript program to display the result of a student</title>
<script type="text/javascript">
function student()
{
    var mark1, mark2, mark3, mark4, mark5, total, percentage;
    mark1 = parseInt(prompt("Enter Subject-1 Marks"));
    mark2 = parseInt(prompt("Enter Subject 2 Marks"));
    mark3 = parseInt(prompt("Enter Subject 3 Marks"));
    mark4 = parseInt(prompt("Enter Subject 4 Marks"));
    mark5 = parseInt(prompt("Enter Subject 5 Marks"));
    total = mark1 + mark2 + mark3 + mark4 + mark5;
    percentage = total / 5;

    if (percentage >= 91 && percentage <= 100)
    {
        alert("O Grade");
    }
    else if (percentage >= 81 && percentage <= 90)
    {
        alert("A+ Grade");
    }
    else if (percentage >= 71 && percentage <= 80)
    {
        alert("A Grade");
    }
    else if (percentage >= 61 && percentage <= 70)
    {
        alert("B+ Grade");
    }
    else if (percentage >= 51 && percentage <= 60)
    {
        alert("B Grade"); 
    }
    else
    {
        alert("RA Grade");
    }
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>


## OUTPUT
![Screenshot 2023-06-15 200806](https://github.com/Madymadesh/Ex06_Web-Design/assets/132973883/da6b3ce5-737b-4b8c-83b5-e1fafc3a8cd2)
![Screenshot 2023-06-15 200818](https://github.com/Madymadesh/Ex06_Web-Design/assets/132973883/b4651136-88ef-4ed4-a2d6-83f77907557c)
![Screenshot 2023-06-15 200642](https://github.com/Madymadesh/Ex06_Web-Design/assets/132973883/eae61d4f-55f2-425a-8deb-24881ded8d27)
![Screenshot 2023-06-15 200711](https://github.com/Madymadesh/Ex06_Web-Design/assets/132973883/95e12a42-c561-4528-b503-ce130a64a072)
![Screenshot 2023-06-15 200723](https://github.com/Madymadesh/Ex06_Web-Design/assets/132973883/272e8d41-c56b-4ba0-97f4-e385d9992636)
![Screenshot 2023-06-15 200740](https://github.com/Madymadesh/Ex06_Web-Design/assets/132973883/3b5d4f63-3449-4d4e-b321-72ea8912f31b)
![Screenshot 2023-06-15 200754](https://github.com/Madymadesh/Ex06_Web-Design/assets/132973883/4b8ee670-f129-43dc-8bc5-3900560ba1e9)


## RESULT
  Student result using JavaScript is created successfully.
