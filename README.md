# Gallardo-activity-4
Php

```php
<!-- LAB 1: Basic If Statement -->
<?php
$age = 18;

if ($age >= 18) {
    echo "You are eligible to vote";
}
?>



<!-- LAB 2: If-Else Statement -->
<?php
$number = -5;

if ($number >= 0) {
    echo "Positive number";
} else {
    echo "Negative number";
}
?>



<!-- LAB 3: If-ElseIf Statement -->
<?php
$grade = 85;

if ($grade >= 90 && $grade <= 100) {
    echo "Excellent";
} elseif ($grade >= 80) {
    echo "Good";
} elseif ($grade >= 70) {
    echo "Average";
} else {
    echo "Failed";
}
?>



<!-- LAB 4: Even or Odd Checker -->
<?php
$num = 7;

if ($num % 2 == 0) {
    echo "Even number";
} else {
    echo "Odd number";
}
?>



<!-- LAB 5: Largest of Three Numbers -->
<?php
$a = 10;
$b = 25;
$c = 15;

if ($a > $b && $a > $c) {
    echo "Largest number is $a";
} elseif ($b > $a && $b > $c) {
    echo "Largest number is $b";
} else {
    echo "Largest number is $c";
}
?>



<!-- LAB 6: Password Checker -->
<?php
$password = "admin123";
$userInput = "admin123";

if ($userInput == $password) {
    echo "Access Granted";
} else {
    echo "Access Denied";
}
?>



<!-- LAB 7: Leap Year Checker -->
<?php
$year = 2024;

if (($year % 4 == 0 && $year % 100 != 0) || ($year % 400 == 0)) {
    echo "$year is a Leap Year";
} else {
    echo "$year is not a Leap Year";
}
?>



<!-- LAB 8: Nested If -->
<?php
$age = 20;
$citizen = "Filipino";

if ($age >= 18) {
    if ($citizen == "Filipino") {
        echo "Eligible to vote";
    } else {
        echo "Not eligible to vote";
    }
} else {
    echo "Not eligible to vote";
}
?>



<!-- LAB 9: Discount Calculator -->
<?php
$amount = 1200;

if ($amount >= 1000) {
    $discount = $amount * 0.20;
} elseif ($amount >= 500) {
    $discount = $amount * 0.10;
} else {
    $discount = 0;
}

$total = $amount - $discount;

echo "Discount: $discount <br>";
echo "Total Amount: $total";
?>



<!-- LAB 10: Simple Login System -->
<?php
$username = "admin";
$password = "1234";

$inputUser = "admin";
$inputPass = "1234";

if ($inputUser == $username && $inputPass == $password) {
    echo "Login Successful";
} else {
    echo "Invalid Username or Password";
}
?>



<!-- LAB 11: Day of the Week -->
<?php
$day = 3;

switch ($day) {
    case 1:
        echo "Monday";
        break;
    case 2:
        echo "Tuesday";
        break;
    case 3:
        echo "Wednesday";
        break;
    case 4:
        echo "Thursday";
        break;
    case 5:
        echo "Friday";
        break;
    case 6:
        echo "Saturday";
        break;
    case 7:
        echo "Sunday";
        break;
    default:
        echo "Invalid input";
}
?>



<!-- LAB 12: Grade Description -->
<?php
$grade = "B";

switch ($grade) {
    case "A":
        echo "Excellent";
        break;
    case "B":
        echo "Good";
        break;
    case "C":
        echo "Average";
        break;
    case "D":
        echo "Poor";
        break;
    case "F":
        echo "Failed";
        break;
    default:
        echo "Invalid Grade";
}
?>



<!-- LAB 13: Simple Calculator -->
<?php
$num1 = 10;
$num2 = 5;
$operator = "+";

switch ($operator) {
    case "+":
        echo $num1 + $num2;
        break;
    case "-":
        echo $num1 - $num2;
        break;
    case "*":
        echo $num1 * $num2;
        break;
    case "/":
        echo $num1 / $num2;
        break;
    default:
        echo "Invalid operator";
}
?>



<!-- LAB 14: Menu Selection -->
<?php
$choice = 2;

switch ($choice) {
    case 1:
        echo "Add Selected";
        break;
    case 2:
        echo "Edit Selected";
        break;
    case 3:
        echo "Delete Selected";
        break;
    default:
        echo "Invalid Choice";
}
?>



<!-- LAB 15: Month Name Generator -->
<?php
$month = 5;

switch ($month) {
    case 1:
        echo "January";
        break;
    case 2:
        echo "February";
        break;
    case 3:
        echo "March";
        break;
    case 4:
        echo "April";
        break;
    case 5:
        echo "May";
        break;
    case 6:
        echo "June";
        break;
    case 7:
        echo "July";
        break;
    case 8:
        echo "August";
        break;
    case 9:
        echo "September";
        break;
    case 10:
        echo "October";
        break;
    case 11:
        echo "November";
        break;
    case 12:
        echo "December";
        break;
    default:
        echo "Invalid Month";
}
?>



<!-- LAB 16: Traffic Light System -->
<?php
$color = "green";

switch ($color) {
    case "red":
        echo "Stop";
        break;
    case "yellow":
        echo "Ready";
        break;
    case "green":
        echo "Go";
        break;
    default:
        echo "Invalid Color";
}
?>
```

