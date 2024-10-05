# Lab2Web.

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

Jawaban :

<img width="227" alt="LabWeb2 1" src="https://github.com/user-attachments/assets/937c0eff-d937-46c5-a630-10f96d639265">

Output :

<img width="375" alt="LabWeb2 2" src="https://github.com/user-attachments/assets/d9e4982f-b7a2-4745-ad9d-5530f40e4473">

2. Apa perbedaan pendeklarasian CSS elemen h1 (...) dengan #intro h1 (..)? berikan penjelasannya!

Jawaban :

Perbedaan pendeklarasian CSS elemen h1 dengan #intro h1
h1 {}: menargetkan semua elemen h1 dalam dokumen HTML.
#intro h1 {}: hanya menargetkan elemen h1 yang berada di dalam elemen dengan id="intro".

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

Jawaban :

CSS inline (prioritas tertinggi)
CSS internal (dalam tag <style> di file HTML)
CSS eksternal (dalam file CSS terpisah)
Jika ketiganya diterapkan pada elemen yang sama, browser akan menampilkan CSS inline karena memiliki prioritas tertinggi.

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! (p id="paragraf-1" class="text-paragraf")

Jawaban :

Jika sebuah elemen memiliki ID dan class, selector ID memiliki spesifisitas lebih tinggi daripada class, jadi umumnya deklarasi ID akan lebih diutamakan jika keduanya mendeklarasikan properti yang sama.
