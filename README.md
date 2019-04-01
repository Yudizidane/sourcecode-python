# sourcecode-python
Microsoft Windows [Version 10.0.17134.648]
(c) 2018 Microsoft Corporation. All rights reserved.

C:\Users\User>python
Python 3.7.1 (default, Dec 10 2018, 22:54:23) [MSC v.1915 64 bit (AMD64)] :: Anaconda, Inc. on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> pins = {"Yudi:123,"Tegar":456,"Ozan":789}
  File "<stdin>", line 1
    pins = {"Yudi:123,"Tegar":456,"Ozan":789}
                           ^
SyntaxError: invalid syntax
>>> quit()

C:\Users\User>python
Python 3.7.1 (default, Dec 10 2018, 22:54:23) [MSC v.1915 64 bit (AMD64)] :: Anaconda, Inc. on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> pins ={"Yudi":1111,"Laras":2222,"LSN":3333}
>>> pins["Yudi"]
1111
>>> pins["Laras"]
2222
>>> pins["LSN"]
3333
>>> pins.keys()
dict_keys(['Yudi', 'Laras', 'LSN'])
>>> pins.values()
dict_values([1111, 2222, 3333])
>>> pins["Setya"]=4444
>>> pins
{'Yudi': 1111, 'Laras': 2222, 'LSN': 3333, 'Setya': 4444}
>>> pins.pop("Setya")
4444
>>> pins
{'Yudi': 1111, 'Laras': 2222, 'LSN': 3333}
>>> masukan = input("Masukan Nama Anda :")
Masukan Nama Anda :Yudi
>>> bilangan=input("Masukan Angka:")
Masukan Angka:18
>>> print (bilangan)
18
>>> print (masukan)
Yudi
>>> print int(input("Masukan Angka:"))
  File "<stdin>", line 1
    print int(input("Masukan Angka:"))
            ^
SyntaxError: invalid syntax
>>> type(masukan)
<class 'str'>
>>> bilangan=int(input("Masukan angka:"))
Masukan angka:18
>>> type(bilangan)
<class 'int'>
>>> print (bilangan**2)
324
>>> bilangan=input("Masukan Angka:")
Masukan Angka:10
>>> type(bilangan)
<class 'str'>
>>> bilangan=int(input("Masukan Angka:"))
Masukan Angka:10
>>> tyoe(bilangan)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'tyoe' is not defined
>>> type(bilangan)
<class 'int'>
>>> print(bilangan/2)
5.0
>>> pins
{'Yudi': 1111, 'Laras': 2222, 'LSN': 3333}
>>> pins.values()
dict_values([1111, 2222, 3333])
>>> kode = 1234
>>> kode in values()
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'values' is not defined
>>> kode in pins.values()
False
>>> kode = 2222
>>> kode in pins.values()
True
>>> if 1<5:
...     print("YES")
... else:
...     print("NO")
...
YES
>>> if 1>9:
...     print("YA")
... else:
...     print("TIDAK")
...
TIDAK
>>> user_input = float(input("Masukan Angka :"))
Masukan Angka :17104018
>>> if user_input > 100000000:
...     print("Greater")
... else:
...     print("Smaller")
...
Smaller
>>> if user_input>20000:
...     print("Lebih Besar")
... else:
...     print("Lebih Kecil")
...
Lebih Besar
>>> def printing():
...     print("Hai")
...     print("Mantan")
...
>>> printing()
Hai
Mantan
>>> def luas_persegi(sisi):
...     luas = sisi*sisi
...     return luas
...
>>> luas_persegi(18(=)
  File "<stdin>", line 1
    luas_persegi(18(=)
                    ^
SyntaxError: invalid syntax
>>> luas_persegi(18)
324
>>> luas_segitiga(100,5)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'luas_segitiga' is not defined
>>> luas_segitiga(18,5)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'luas_segitiga' is not defined
>>> def luas_segitiga(sisi):
... def hitung_umur(lahir):
  File "<stdin>", line 2
    def hitung_umur(lahir):
      ^
IndentationError: expected an indented block
>>> def hitung_umur(kelahiran):
...     umur = (2019 - kelahiran)
...     print("Umur saya dong : %d" %umur)
...
>>> hitung_umur(1998)
Umur saya dong : 21
>>>
