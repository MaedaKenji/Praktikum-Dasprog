# Penjumlahan Deret Angka Menggunakan Rekursi

## Deskripsi  
Program ini bertujuan untuk menghitung **penjumlahan deret angka dari 1 hingga n** menggunakan **rekursi**. Rekursi adalah metode pemanggilan fungsi di mana sebuah fungsi memanggil dirinya sendiri hingga mencapai kondisi tertentu (base case).

**Contoh**:
```  
n = 4
Hasil penjumlahan deret dari 1 hingga 4 adalah: 10


n = 5
Hasil penjumlahan deret dari 1 hingga 5 adalah: 15

n = 0
Hasil penjumlahan deret dari 1 hingga 0 adalah: 0
```


## Spesifikasi Program  
- Fungsi bernama `jumlahDeret` akan menerima satu parameter `n`, yang merupakan batas atas deret.
- Fungsi akan mengembalikan hasil penjumlahan dari semua angka mulai dari 1 hingga n.

## Rumus Rekursi
- jumlahDeret(n) = n + jumlahDeret(n - 1), jika n > 0 
- jumlahDeret(0) = 0, sebagai base case