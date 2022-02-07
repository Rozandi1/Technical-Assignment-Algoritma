## Algoritma
Write a program that prints the numbers from 1 to n

for multiples of 3 print "Fizz" instead of the number
for the multiples of 5 print "Buzz" instead of the number
for numbers which are multiplies of both 3 and 5 print "FizzBuzz"
for numbers not divisible by, 3, 5, or both, print the number as is


## Pseudocode

STORE N WITH ANY NUMBER
STORE i WITH 0
WHILE i LESS THAN N
    STORE currenValue WITH i PLUS 1
    IF (currentValue MODULUS BY 3 EQUAL 0)
        DISPLAY "Fizz"
    ELSE IF (currentValue MODULUS BY 5 EQUAL 0)
        DISPLAY "FizzBuzz"
    ELSE
        DISPLAY currentValue
    End IF
        SET i WITH i PLUS 1
    END WHILE