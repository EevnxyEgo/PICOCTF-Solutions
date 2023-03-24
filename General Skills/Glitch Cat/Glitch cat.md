# Glitch cat

## Overview

Points: 100
Category: General Skills

## Description

> Our flag printing service has started glitching!
$ nc saturn.picoctf.net 53638

## Hints

1. ASCII is one of the most common encodings used in programming
2. We know that the glitch output is valid Python, somehow!
3. Press Ctrl and c on your keyboard to close your connection and return to the command prompt.

## Langkah penyelesaian
1. Pertama download netcat for Windows di [link berikut](https://nmap.org/) dan lakukan instalasi sampai selesai.
2. Buka CMD atau Windows PowerShell lalu ketikkan instruksi `ncat saturn.picoctf.net 53638`
3. Pada terminal akan  menampilkan output berikut:
>'picoCTF{gl17ch_m3_n07_' + chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35) + '}'

4. untuk mendapatkan flag copy output tersebut dan paste pada IDLE kemudian klik Enter.


## Flag

picoCTF{gl17ch_m3_n07_bda68f75}
