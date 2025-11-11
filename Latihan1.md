PROJECT-SO-ANSAR HALIDI-
Project Based Learing 1

LANGKAH 1 BUAT STRUKTUR DIREKTORI Berikut contoh Membuat Direkoti Project_File_Management:

```
#ubuntu@tugasansar:~mkdir latihan1_SistemOperasi
```

Berikut contoh perintah Berpindah Direktori ke Project_File_Management dan Membuat folder document images archives logs:

```
cd Project_File_Management
```
```
mkdir document images archives logs
```

Berikut contoh perintah membuat file sample:

```
touch file{1..10}.txt file{11..15}.jpg file{16..18}.pdf file{19..20}.log
```

Berikut contoh perintah memasukan sebuah teks ke masing masing file yang berbeda:

```
echo "Ini adalah dokumen contoh" > file1.txt
```
```
echo "Data gambar" > file11.jpg
```
```
echo "Log sistem contoh" > file20.log
```

[Deskripsi gambar] https://drive.google.com/file/d/1hvRiMQlNIGRIR4gKuczb0L9GH3yDzrIj/view?usp=drivesdk


Penjelasan:

mkdir → membuat folder baru.

touch → membuat file kosong dengan cepat.

echo → menulis teks ke dalam file.
