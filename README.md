# 21_M-Rasya-Arkhan-Hidayat_Tugas_OOP

Analisis Praktikum 1-6

📌 Analisis Penerapan Konsep OOP (Tugas 1–6)

Program ini merupakan simulasi sederhana pertarungan antar karakter game yang dirancang untuk menerapkan konsep Object-Oriented Programming (OOP) dalam bahasa Python. Kode dibagi ke dalam beberapa bagian sesuai dengan tujuan masing-masing tugas.

Tugas 1 – Class & Object

Pada tugas ini, konsep class dan object diterapkan dengan membuat class Hero sebagai blueprint karakter dalam game. Class ini memiliki atribut seperti name, hp, dan attack_power. Objek dari class Hero kemudian dibuat pada bagian main program untuk merepresentasikan karakter nyata yang dapat berinteraksi di dalam permainan.

Tugas 2 – Interaksi Antar Objek

Interaksi antar objek ditunjukkan melalui method serang() dan diserang(). Objek Hero dapat menyerang objek lain dan memberikan damage, sedangkan objek yang diserang akan menerima pengurangan HP. Hal ini menggambarkan bagaimana objek dalam OOP dapat saling berkomunikasi dan memengaruhi satu sama lain.

Tugas 3 – Inheritance (Pewarisan)

Konsep inheritance diterapkan dengan membuat class Mage yang mewarisi class Hero. Dengan menggunakan fungsi super(), class Mage dapat memanfaatkan atribut dan method milik Hero tanpa perlu menuliskan ulang kode. Pendekatan ini meningkatkan efisiensi dan menjaga struktur program tetap terorganisir.

Tugas 4 – Encapsulation (Enkapsulasi)

Enkapsulasi diterapkan dengan menjadikan atribut hp sebagai atribut private (__hp). Akses terhadap HP dilakukan melalui method getter dan setter, sehingga nilai HP dapat divalidasi dan dijaga agar tidak berada di luar batas logis, seperti bernilai negatif atau melebihi batas maksimum.

Tugas 5 – Abstraction (Abstraksi)

Abstraksi diterapkan melalui abstract class GameUnit yang mendefinisikan method abstrak serang() dan info(). Class ini berfungsi sebagai kontrak yang harus diikuti oleh class turunannya. Dengan adanya abstraksi, struktur program menjadi lebih konsisten dan mudah dikembangkan.

Tugas 6 – Polymorphism (Polimorfisme)

Polimorfisme ditunjukkan dengan melakukan override method serang() pada class Mage. Meskipun memiliki nama method yang sama dengan class Hero, implementasinya berbeda. Mage dapat melakukan serangan khusus menggunakan mana, sementara jika mana tidak mencukupi, serangan akan kembali ke perilaku default milik Hero.

🧾 Kesimpulan

Melalui penerapan enam konsep OOP tersebut, program ini menunjukkan bagaimana desain berbasis objek dapat membuat kode lebih terstruktur, fleksibel, dan mudah dikembangkan. Setiap konsep saling melengkapi untuk membangun sistem yang realistis dan efisien, sehingga cocok digunakan sebagai latihan dasar pemrograman berorientasi objek.
