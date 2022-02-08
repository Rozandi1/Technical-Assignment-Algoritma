## Algoritma
Program mengkonversi Suhu

Kamu adalah seorang mahasiswa IT yang baru memulai perjalanan, kemudian kamu juga sudah belajar tentang adanya pseudocode. Kemudian dosenmu memmberikan sebuah tugas untuk membuat sebuah pseudocode tentang cara kerja sebuah thermometer yang akan merubah semua jenis suhu menjadi celcius.
Berikut adalah 3 cara konversi suhu ke dalam celcius:

fahrenheit to celcius = (N - 32) * (5/9)
kelvin to celcius = (N - 273.15)
celcius to celcius = N

## Pseudocode
START
STORE N as integer with any value
STORE type as string with any value
STORE result as integer
IF (type equal fahrenheit)
    calculate (N - 32) * (5/9)
    SET result with calculation result
Else IF (type equal celcius)
    calculate (N)
    SET result with calculation result
end IF
DISPLAY result  