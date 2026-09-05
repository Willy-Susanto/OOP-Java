# ☕ Java OOP: Teori, Konsep & Implementasi Langsung

Halo, selamat datang! 👋

Repo ini berisi catatan belajar OOP Java yang disusun bertahap, mulai dari dasar sampai ke design pattern. Setiap modul punya dua bagian: penjelasan konsep dan contoh kode yang langsung bisa dijalankan, jadi nggak cuma teori doang.

Urutannya sengaja dibuat nyambung satu sama lain, tapi kamu juga bebas loncat ke modul mana pun yang paling relevan dengan yang lagi dipelajari sekarang.

## 📚 Daftar Modul

| # | Modul | Yang Akan Dipelajari |
|:--|:------|:---------------------|
| 01 | **Fondasi OOP** | Kenapa OOP ada, bedanya sama pendekatan prosedural, dan cara berpikir dalam objek |
| 02 | **Kelas, Objek & Enkapsulasi** | Bikin class yang rapi, constructor, access modifier, getter-setter, dan validasi data |
| 03 | **Pewarisan (Inheritance)** | Hirarki class, keyword `extends` & `super`, dan method overriding |
| 04 | **Polimorfisme & Abstraksi** | Overloading vs overriding, dynamic binding, abstract class, dan interface |
| 05 | **Relasi Antar Objek** | Kapan pakai asosiasi, agregasi, atau komposisi dan bedanya |
| 06 | **Java Generics** | Type safety, class generic `<T>`, wildcard, dan kegunaannya di berbagai kasus |
| 07 | **Exception Handling** | Error yang ditangani dengan elegan: try-catch-finally, checked vs unchecked, custom exception |
| 08 | **Object Persistence I** | Nyimpen objek ke file lewat File I/O dan serialisasi Java |
| 09 | **Object Persistence II** | Baca-tulis JSON/CSV dan pengenalan JDBC untuk koneksi ke database |
| 10 | **Prinsip SOLID** | Lima prinsip desain yang bikin kode gampang dirawat dan dikembangkan |
| 11 | **Design Pattern: Creational & Structural** | Singleton, Factory, Builder, Adapter dan pola pembentukan objek lainnya |
| 12 | **Design Pattern: Behavioral** | Strategy, Observer, dan pola komunikasi antar objek |

## 📂 Struktur Folder

```
java-oop/
├── 01_Fondasi_OOP/
├── 02_Kelas_Objek_Enkapsulasi/
├── 03_Pewarisan/
├── 04_Polimorfisme_Abstraksi/
├── 05_Relasi_Objek/
├── 06_Generic_Class/
├── 07_Exception_Handling/
├── 08_Object_Persistence_I/
├── 09_Object_Persistence_II/
├── 10_SOLID_Principles/
├── 11_Design_Pattern_Creational_Structural/
├── 12_Design_Pattern_Behavioral/
└── README.md
```

## 🚀 Cara Jalankan

Pastikan sudah ada **Java JDK 17+** dan IDE atau terminal yang siap dipakai, lalu:

```bash
cd 03_Pewarisan
javac Main.java
java Main
```

Setiap folder sudah dilengkapi komentar di dalam kodenya, jadi cukup baca dari sana kalau mau tahu konteksnya.
