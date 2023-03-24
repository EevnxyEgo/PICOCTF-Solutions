# PW Crack 1

## Overview

Points: 100
Category: General Skills

## Description

> Can you crack the password to get the flag?
Download the password checker here and you'll need the encrypted flag in the same directory too.

## Hints

1. To view the file in the webshell, do: `$ nano level1.py`
2. To exit `nano`, press Ctrl and x and follow the on-screen prompts.
3. The `str_xor` function does not need to be reverse engineered for this challenge.

## Langkah penyelesaian
1. Download file Password checker di [link berikut](https://artifacts.picoctf.net/c/10/level1.py)
2. Buka file yang telah didownload yaitu level1.py menggunakan text editor (disini saya menggunakan IDLE)
```python
def level_1_pw_check():
    user_pw = input("Please enter correct password for flag: ")
    if( user_pw == "8713"):
        print("Welcome back... your flag, user:")
        decryption = str_xor(flag_enc.decode(), user_pw)
        print(decryption)
        return
    print("That password is incorrect")
```
Disini dapat dilihat bahwa password yang benar adalah `8713`


3. Run file level1,py dan masukkan password maka akan muncul flag yang dicari.

## Flag

picoCTF{545h_r1ng1ng_1b2fd683}
