# Tugas PBO
Functional programming dan OOP (Object-Oriented Programming) adalah dua paradigma pemrograman yang berbeda dalam cara mereka memetakan solusi masalah. Di Python, Anda dapat menggunakan keduanya atau bahkan menggabungkannya.

Berikut adalah perbedaan antara Functional Programming dan OOP pada Python Beserta kode contoh pda program masing masing:

1.) Functional programming didasarkan pada pemikiran matematis, dengan fokus pada fungsi murni (pure function) yang menerima argumen dan mengembalikan nilai tanpa mengubah argumen atau variabel global lainnya. Beberapa ciri utama dari functional programming adalah tidak adanya side effect dan immutable data.

Penjealasan Program pada contoh program 1,Pada kode tersebut, terdapat tiga fungsi:

add(a, b): Fungsi pure untuk menambahkan dua angka. Fungsi ini menerima dua parameter a dan b, dan mengembalikan hasil penjumlahan a dan b.
subtract(a, b): Fungsi pure untuk mengurangi dua angka. Fungsi ini menerima dua parameter a dan b, dan mengembalikan hasil pengurangan a dan b.
apply(func, data): Fungsi yang menerima dua parameter, yaitu fungsi func dan data data. Fungsi ini akan mengembalikan daftar hasil dari memanggil fungsi func pada setiap item di dalam data.
Kemudian, kita melakukan dua contoh penggunaan apply dengan menggunakan fungsi add dan subtract sebagai parameter func. Pada contoh pertama, kita membuat daftar angka [1, 2, 3, 4, 5], dan memanggil apply dengan parameter add dan numbers. Fungsi apply akan memanggil fungsi add untuk setiap item di dalam numbers, dan mengembalikan daftar hasilnya. Hasilnya akan disimpan di variabel result dan dicetak menggunakan perintah print(result).

Pada contoh kedua, kita melakukan hal yang sama dengan menggunakan fungsi subtract sebagai parameter func. Kembali, hasilnya akan dicetak menggunakan perintah print(result).

2.) OOP didasarkan pada konsep objek, di mana suatu objek memiliki atribut (properti) dan metode (fungsi). Objek dapat berinteraksi satu sama lain melalui metode dan mewarisi properti dan metode dari kelas yang lebih umum. Pemrograman berorientasi objek bertujuan untuk mengorganisasi kode menjadi modul yang saling terkait dan memudahkan pengembangan aplikasi yang kompleks.

Penjelasan Program pada contoh program 2, Pada kode tersebut, terdapat sebuah kelas Calculator yang memiliki dua metode, yaitu add dan subtract. Metode add digunakan untuk melakukan penjumlahan antara dua angka, sedangkan metode subtract digunakan untuk melakukan pengurangan antara dua angka.

Ketika sebuah objek Calculator dibuat dengan memanggil kelas tersebut, nilai num1 dan num2 akan disimpan di dalam objek sebagai atribut self.num1 dan self.num2. Pada saat pemanggilan metode add dan subtract, objek tersebut akan menggunakan nilai num1 dan num2 yang disimpan pada atributnya untuk melakukan perhitungan dan mengembalikan hasilnya.

Kemudian, kita membuat sebuah objek calculator dengan memanggil kelas Calculator dan memberikan nilai 10 dan 5 sebagai argumen pada saat pembuatan objek. Setelah objek calculator dibuat, kita memanggil metode add dan subtract pada objek tersebut dengan menggunakan perintah calculator.add() dan calculator.subtract(). Hasil perhitungan akan dicetak ke layar menggunakan perintah print. Pada contoh tersebut, hasil dari calculator.add() adalah 15 dan hasil dari calculator.subtract() adalah 5.
