labpy03
(latihan 1)
``` python
import random

n= input("masukan nilai N: 5")

for x in range (1,6):

 print("data ke:",x,"=>",random.uniform(0.0,0.5))  
 ```
 Pengacakan, pembangkit bilangan acak, atau random dapat digunakan untuk berbagai macam hal. Salah satunya adalah untuk memecahkan kasus Monte Carlo. Nilai random kadang dibutuhkan juga untuk menentukan suatu pilihan. Atau digunakan juga untuk membuat id yang ditambahi dari string asal. Randomisasi juga dapat digunakan untuk mengacak suatu tampilan produk, atau digunakan saat proses pelatihan sebuah mesin cerdas.
 
 ![screenshot 34](https://user-images.githubusercontent.com/46917932/52928254-64faf480-3371-11e9-9418-4a6e50755242.png)
 
(latihan 2)
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

![screenshot 33](https://user-images.githubusercontent.com/46917932/52929024-1d766780-3375-11e9-8f08-aa9459ff4af3.png)


(latihan 3)
```python

for x in range(1,9):

    if(x>=1 and x<=2):
    
        b = a*0
        
        print("Laba Bulan ke-",x," :",b)
        
    if(x>=3 and x<=4):
    
        b = a*1
        
        print("Laba Bulan ke-",x," :",c)
        
    if(x>=1 and x<=7):
    
        b = a*5
        
        print("Laba Bulan ke-",x," :",d)
        
    if(x==8):
    
        e=a*0.2
        
        print("Laba Bulan ke-",x," :",e)
        
total = b+b+c+c+d+d+d+e

print("\ntotal : ", total)
```
Fungsi range() sering digunakan sebagai counter pada perulangan for. Counter adalah sebuah variabel yang menyimpan hitungan—berapa kali mengulang—perulangan. 

![screenshot 33](https://user-images.githubusercontent.com/46917932/52929024-1d766780-3375-11e9-8f08-aa9459ff4af3.png)
