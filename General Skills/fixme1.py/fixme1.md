# fixme1.py

## Overview

Points: 100
Category: General Skills

## Description

>Fix the syntax error in this Python script to print the flag.
Download Python script

## Hints

1. Indentation is very meaningful in Python
2. To view the file in the webshell, do: `$ nano fixme1.py`
3. To exit `nano`, press Ctrl and x and follow the on-screen prompts.
4. The `str_xor` function does not need to be reverse engineered for this challenge.

## Langkah penyelesaian
1. Download file [Python script](https://artifacts.picoctf.net/c/27/fixme1.py)
2. gunakan text editor untuk file `fixme1.py` untuk  menemukan error di dalam script python tersebut. (Disini saya menggunakan IDLE)
```python
flag = str_xor(flag_enc, 'enkidu')
 print('That is correct! Here\'s your flag: ' + flag)

```
Pada line terakhir dapat dilihat bahwa terdapat kesalahan indentasi pada instruksi print.
3. setelah berhasil menemukan kesalahan dalam file tersebut dan memperbaikinya, selanjutnya run file untuk mendapatkan flag.



## Flag

picoCTF{1nd3nt1ty_cr1515_182342f7}
