# Implementasi Linked List dalam Python

Repositori ini berisi kumpulan skrip Python yang mendemonstrasikan implementasi dan operasi dasar dari struktur data *Singly Linked List*. Setiap file berfokus pada metode atau fungsionalitas tertentu dari *linked list*.

---

## Deskripsi

*Linked list* adalah struktur data linier di mana elemen-elemennya tidak disimpan di lokasi memori yang berdekatan. Setiap elemen (disebut **node**) berisi data dan referensi (*pointer*) ke *node* berikutnya dalam urutan. Skrip-skrip ini mengilustrasikan cara membuat *linked list* dari awal dan melakukan operasi umum seperti menambahkan, menyisipkan, dan mengakses elemen.

---

## Daftar Skrip dan Metode yang Diimplementasikan

Berikut adalah rincian dari setiap skrip yang disertakan:

### 1. `Append.py` & `Append (1).py`

* **Metode:** `append(value)`
* **Deskripsi:** Skrip ini menunjukkan cara menambahkan elemen baru ke **akhir** *linked list*. Metode `append` membuat *node* baru dan menautkannya setelah *tail* (elemen terakhir) saat ini, lalu memperbarui *tail* ke *node* yang baru.
* **Untuk Menjalankan:**
    ```bash
    python Append.py
    ```

### 2. `PREPEND.py`

* **Metode:** `prepend(value)`
* **Deskripsi:** Mengimplementasikan penambahan elemen baru di **awal** *linked list*. Metode `prepend` membuat *node* baru, mengarahkannya ke *head* (elemen pertama) saat ini, dan kemudian memperbarui *head* menjadi *node* yang baru.
* **Untuk Menjalankan:**
    ```bash
    python PREPEND.py
    ```

### 3. `GET.py`

* **Metode:** `get(index)`
* **Deskripsi:** Skrip ini menunjukkan cara **mengambil** (mendapatkan) sebuah *node* pada indeks tertentu dalam *linked list*. Metode `get` akan melintasi daftar dari *head* hingga mencapai posisi indeks yang diinginkan.
* **Untuk Menjalankan:**
    ```bash
    python GET.py
    ```

### 4. `SET.py`

* **Metode:** `set_value(index, value)`
* **Deskripsi:** Mengimplementasikan cara **mengubah nilai** dari sebuah *node* pada indeks tertentu. Metode ini pertama-tama menggunakan metode `get` untuk menemukan *node* pada indeks yang diberikan, lalu memperbarui nilainya.
* **Untuk Menjalankan:**
    ```bash
    python SET.py
    ```

### 5. `INSERT.py`

* **Metode:** `insert(index, value)`
* **Deskripsi:** Skrip ini menunjukkan cara **menyisipkan** elemen baru pada indeks tertentu di dalam *linked list*. Metode ini menangani kasus-kasus khusus seperti penyisipan di awal (menggunakan `prepend`), di akhir (menggunakan `append`), atau di tengah-tengah daftar.
* **Untuk Menjalankan:**
    ```bash
    python INSERT.py
    ```

---

## Cara Menggunakan

1.  **Clone Repositori:**
    ```bash
    git clone https://github.com/Mystery230/Linked-List.git
    cd Linked-List
    ```
2.  **Jalankan Skrip:**
    Anda dapat menjalankan setiap file secara individual menggunakan Python untuk melihat bagaimana setiap metode memanipulasi dan menampilkan *linked list*.
    ```bash
    python Append.py

    python PREPEND.py

    python GET.py

    python SET.py

    python INSERT.py

    ```
