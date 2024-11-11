# Tugas Praktikum

Buat program sederhana untuk menambahkan data kedalam sebuah list dengan rincian sebagai berikut:

- Progam meminta memasukkan data sebanyak-banyaknya (gunakan perulangan)

- Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban t (Tidak), maka program akan menampilkan daftar datanya.

- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)

- Buat flowchart dan penjelasan programnya

# Tampilan Program

1. Flowchart

![Flowchart (8)](https://github.com/user-attachments/assets/ea6c39a4-d87b-47e0-a6c4-0ffa9a2ad2cf)

2. Program Python

![image](https://github.com/user-attachments/assets/c16d2297-759e-4a70-889e-3e0d0c8eb55c)

![image](https://github.com/user-attachments/assets/dde3f2df-d8cc-4e92-ba40-9a0805416ae3)

3. Penjelasan

  - Inisialisasi List: Program dimulai dengan membuat list kosong data_mahasiswa untuk menyimpan data masing-masing mahasiswa.
  
  - Perulangan Utama: Program menggunakan while True untuk menjalankan perulangan terus-menerus agar user bisa memasukkan data sebanyak mungkin.
  
  - Memasukkan Data:
  
    - Program meminta user memasukkan nama, NIM, nilai tugas, nilai UTS, dan nilai UAS untuk setiap mahasiswa.
     
    - Program menghitung nilai akhir berdasarkan rumus: (tugas * 0.30) + (uts * 0.35) + (uas * 0.35).
  
  - Menyimpan Data:
  
    - Data mahasiswa (nama, NIM, tugas, UTS, UAS, dan nilai akhir) disimpan dalam dictionary, kemudian dictionary tersebut ditambahkan ke data_mahasiswa sebagai elemen baru.
  
  - Pertanyaan Penambahan Data:
  
    - Program meminta user memilih untuk menambah data lagi atau tidak dengan memasukkan 'y' untuk menambah atau 't' untuk berhenti.
  
    - Jika user memilih 't', perulangan berhenti dan program lanjut ke bagian menampilkan data.
    
  - Menampilkan Data dalam Tabel:
  
    -  Program mencetak tabel yang memuat seluruh data mahasiswa yang sudah dimasukkan. Setiap baris berisi nomor, nama, NIM, nilai tugas, UTS, UAS, dan nilai akhir dengan format yang rapi.

4. Input & Output

   ![image](https://github.com/user-attachments/assets/eb62650c-a32e-42aa-8fa1-13bc876e618d)
