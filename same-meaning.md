## Algoritma

Palindrome adalah adanya sebuah kata, frasa, atau angka yang dapat dibaca dengan sama baik dari depan maupun belakang.

Buatlah sebuah program untuk mengecek apakah 1 buah nilai bersifat palindrome. Jika iya program akan mengembalikan status TRUE jika tidak program akan mengembalikan status FALSE.

Input hanya dapat menerima tipe data berupa string/teks.

## Pseudocode

STORE "input" with any STRING
STORE "palindrom"
FOR "input" FROM "input" index "input" length -1 TO "input"
    SET "palindrom" WITH "palindrom" CONCAT WITH "input" index "input"
END FOR
IF "input" is equal "palindrom"
    DISPLAY "TRUE"
ELSE
    DISPLAY "FALSE"
END IF