# fixme2.py

## Overview

Points: 100
Category: General Skills

## Description

>Fix the syntax error in this Python script to print the flag.
Download Python script

## Hints

1. Are equality and assignment the same symbol?
2. To view the file in the webshell, do: `$ nano fixme2.py`
3. To exit `nano`, press Ctrl and x and follow the on-screen prompts.
4. The `str_xor` function does not need to be reverse engineered for this challenge.

## Langkah penyelesaian
1. Download file [Python script](https://artifacts.picoctf.net/c/4/fixme2.py)
2. gunakan text editor untuk file `fixme2.py` untuk  menemukan error di dalam script python tersebut. (Disini saya menggunakan IDLE)
```python
# Check that flag is not empty
if flag = "":
  print('String XOR encountered a problem, quitting.')
else:
  print('That is correct! Here\'s your flag: ' + flag)

```
Pada bagian if dapat dilihat bahwa operator yang digunakan untuk mengecek kondisi adalah `=` dimana itu merupakan assignment operator, seharusnya operator yang digunakan adalah `==` sebagai komparator antara dua operand apakah bernilai equal atau tidak.

3. setelah berhasil menemukan kesalahan dalam file tersebut dan memperbaikinya, selanjutnya run file untuk mendapatkan flag



## Flag

picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}
