labpy03
(praktikum1.py)
``` python
import random

n= input("masukan nilai N: 5")

for x in range (1,6):

 print("data ke:",x,"=>",random.uniform(0.0,0.5))  
 ```
 Pengacakan, pembangkit bilangan acak, atau random dapat digunakan untuk berbagai macam hal. Salah satunya adalah untuk memecahkan kasus Monte Carlo. Nilai random kadang dibutuhkan juga untuk menentukan suatu pilihan. Atau digunakan juga untuk membuat id yang ditambahi dari string asal. Randomisasi juga dapat digunakan untuk mengacak suatu tampilan produk, atau digunakan saat proses pelatihan sebuah mesin cerdas.
 
 ![screenshot 34](https://user-images.githubusercontent.com/46917932/52928254-64faf480-3371-11e9-9418-4a6e50755242.png)
 
 ```python
 max=0
 
while True:

    a=int(input("masukan bilangan:"))
    
    if a ==0:
    
        break
        
    if a>max:
    
        max=a
        
print("bilangan terbesar:",max)
```

Melakukan perulangan dengan while, kemudian menambah satu variabel hitung setiap kali mengulang. lalu menanyakan kepada pengguna, apakah mau berhenti mengulang atau tidak?

![screenshot 35](https://user-images.githubusercontent.com/46917932/52928566-00409980-3373-11e9-87f2-eedefec892ab.png)
