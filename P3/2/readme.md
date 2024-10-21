# Membalik Array Menggunakan Rekursi

## Deskripsi  
Program ini bertujuan untuk membalikkan urutan elemen di dalam sebuah array dengan menggunakan **rekursi**. Dalam program ini, elemen pertama dan terakhir akan ditukar secara berulang hingga seluruh elemen berada dalam urutan terbalik.

Contoh:  
Jika diberikan array `[1, 2, 3, 4, 5]`, setelah dibalik akan menjadi `[5, 4, 3, 2, 1]`.

---

## Spesifikasi Program  
- Fungsi bernama `balikArray` akan menerima array dan dua indeks, yaitu **`start`** dan **`end`**.
- Fungsi akan menukar elemen pada posisi `start` dengan `end`, kemudian memanggil dirinya sendiri dengan nilai `start + 1` dan `end - 1` hingga kondisi base case tercapai.

---
## Rumus Rekursi  

- balikArray(arr, start, end) = 
    tukar(arr[start], arr[end])
    - panggil balikArray(arr, start + 1, end - 1) jika start < end
    - balikArray(arr, start, end) berhenti jika start >= end