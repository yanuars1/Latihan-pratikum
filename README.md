DWI YANUAR PRASETIA 
24.TI.A1
# Program Mencari Bilangan Terbesar
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.
## Deskripsi Program
Program ini dibuat menggunakan bahasa Python dengan fitur:

- Menggunakan while True untuk perulangan tak terbatas
- Menggunakan break statement untuk menghentikan program
- Membandingkan setiap input dengan nilai maksimum yang tersimpan
- Menampilkan bilangan terbesar yang ditemukan

## Flowchart Programan
![flowchart](Flowchart.png)

## Kode Program
```Python
max = 0
bilangan = int(input("masukan bilangan :"))
while bilangan != 0 :
    if bilangan > max :
        max = bilangan 
    bilangan = int(input("masukan bilangan :"))
    
print (f"bilangan terbesar= {max}")
```

## Output Program
````
masukan bilangan :478
masukan bilangan :125
masukan bilangan :853
masukan bilangan :999
masukan bilangan :257
masukan bilangan :0
bilangan terbesar= 999
````

## Cara Kerja Program
Pada tahap awal, Python akan meminta pengguna memasukkan bilangan berulang kali. Jika bilangan lebih besar dari nilai sebelumnya, bilangan tersebut disimpan sebagai yang terbesar. Proses berhenti saat pengguna memasukkan 0, dan program mencetak bilangan terbesar yang telah dimasukkan.




![Uploading image.png…]()
