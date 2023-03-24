# Nice netcat

## Overview

Points: 15
Category: General Skills

## Description

> There is a nice program that you can talk to by using this command in a shell: $ nc mercury.picoctf.net 43239, but it doesn't speak English...

## Hints

1. You can practice using netcat with this picoGym problem: [what's a netcat?](https://play.picoctf.org/practice/challenge/34)
2. You can practice reading and writing ASCII with this picoGym problem: [Let's Warm Up](https://play.picoctf.org/practice/challenge/22)

## Langkah penyelesaian

1. Pertama download netcat for Windows di [link berikut](https://nmap.org/) dan lakukan instalasi sampai selesai.
2. Buka CMD atau Windows PowerShell lalu ketikkan instruksi `ncat mercury.picoctf.net 22902`
3. Pada terminal akan menampilkan angka-angka berikut:
> 112
105
99
111
67
84
70
123
103
48
48
100
95
107
49
116
116
121
33
95
110
49
99
51
95
107
49
116
116
121
33
95
100
51
100
102
100
54
100
102
125
10

Angka-angka tersebut merupakan ASCII value untuk text.

4. Gunakan Decimal to ASCII converter untuk mendapatkan flag, bisa menggunakan online converter seperti pada [link ini](https://www.rapidtables.com/convert/number/ascii-hex-bin-dec-converter.html).



## Flag

picoCTF{g00d_k1tty!_n1c3_k1tty!_d3dfd6df}
