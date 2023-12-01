# Real-Time-Face-Recognition (OpenCV)

Buat aplikasi pengenalan wajah real-time yang cepat dengan beberapa baris kode python.

## Langkah:

`cmd: python face_taker.py` 

1) Ambil gambar menggunakan skrip `face_taker.py`. Script akan menyimpan 30 gambar wajah Anda di folder `gambar` setelah Anda memasukkan nomor ID (HARUS bilangan bulat dan inkremental (dimulai dengan 1 lalu 2, 3, ...) Catatan: Pastikan wajah Anda berada di tengah. Jendela akan runtuh ketika 30 gambar diambil.


`cmd: python face_train.py`

2) Skrip `face_tain.py` akan melatih model untuk mengenali semua wajah dari 30 gambar yang diambil menggunakan skrip `face_taker.py`, dan menyimpan keluaran pelatihan di file `training.yml`.


`cmd: python face_recognizer.py`

3) `face_recognizer.py` adalah skrip utama. Anda perlu menambahkan nama setiap orang dengan gambar yang diambil di skrip `face_taker.py`. Program akan mengenali wajah sesuai dengan id yang diberikan dalam skrip `face_taker.py`.

4) Jika Elviana memiliki id 1, namanya akan muncul dalam daftar sebagai indeks 1 seperti `names = ['None', 'Elviana'] #tidak menyimpan apa pun dan tambahkan nama ke dalam daftar ini'

## Persyaratan:

- `pip install opencv-python`
- `pip install opencv-contrib-python --upgrade` or `pip install opencv-contrib-python --user.`
