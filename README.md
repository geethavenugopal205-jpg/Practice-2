<?php

$name = "Geetha";
$birthYear = 2005;
$currentYear = 2026;
$retirementAge = 60;

$age = $currentYear - $birthYear;
$remainingYears = $retirementAge - $age;

echo "Employee Name: " . $name . "<br>";
echo "Current Age: " . $age . "<br>";

if ($remainingYears > 0) {
    echo "Years Remaining for Retirement: " . $remainingYears;
} else {
    echo "Employee has reached retirement age.";
}

?>
Employee Name: Geetha
Current Age: 21
Years Remaining for Retirement: 39
