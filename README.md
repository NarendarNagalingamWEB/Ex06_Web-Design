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

```


## OUTPUT
![2023-05-27 (5)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/0b43cc99-9853-44da-9290-260e2680a1ca)
![2023-05-27 (6)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/be1648cc-7882-406b-a931-b687282069bc)
![2023-05-27 (8)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/fee4f00b-2ea5-4c30-96d6-906db39db807)
![2023-05-27 (9)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/adb9b883-776a-496a-8c2e-f14ab0a5877e)
![2023-05-27 (10)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/098a6279-2a18-44c3-b512-e15ae5a3fd41)
![2023-05-27 (11)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/67ecb58c-96d9-460b-8b8a-7da5f869fb57)
![2023-05-27 (12)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/8cb40ec2-d7d3-449e-86f1-5b851fb0df88)
![2023-05-27 (13)](https://github.com/NarendarNagalingamWEB/Ex06_Web-Design/assets/128288529/7515031b-1a0f-4872-832b-a158fdc5a836)

## RESULT
  Student result using JavaScript is created successfully.
