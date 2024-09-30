# Assignment 6 Soal 1
<div> </div>

Di sebuah toko buku terdapat berbagai kategori: **FIKSI**, **NONFIKSI**, **SAINS**, **SEJARAH**, dan **KOMIK**. Buat enum `KategoriBuku` yang mencakup **harga** dan **status ketersediaan**. Tambahkan inner class `DetailBuku` untuk menyimpan **penulis** dan **tahun terbit**.

Buat Method `getDeskripsi()` yang menampilkan deskripsi lengkap (kategori, ketersediaan, dan detail buku) dan Method `getHarga()` yang mengembalikan harga buku.


**Contoh Kode**:

<div class='flex-column' style="overflow-y: auto; max-height: 250px; max-width: 100%;">

```java
public enum KategoriBuku {
  FIKSI(/* harga, ketersediaan */), 
  NONFIKSI(/* harga, ketersediaan */),
  ...

  public String getDeskripsi() { ... };
  public int getHarga() { ... };

  // Inner class
  class DetailBuku {
    private String penulis;
    private int tahunTerbit;
    ...
  }
}
```
</div>