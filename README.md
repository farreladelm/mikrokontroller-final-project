# Final Project Mikrokontroller (kelompok 8)

## Anggota:
- Farrel Adel Mohammad          -   20081010138
- Muhammad Abi Prakosa          -   20081010232
- Salma Fathiyatur Rizky Munir  -   20081010025
- Sabrina Laila Sari            -   20081010224

## Modul yang digunakan:
- Riset Deep Learning untuk Penalaan Parameter PID pada Kit iTCLab dan Pemantauannya Menggunakan Internet of Things(IoT) 

## Modifikasi yang dilakukan:
- Penggunaan fungsi aktivasi ReLU untuk lapisan tersembunyi (activation='relu').
- Penambahan dua lapisan tersembunyi tambahan dengan fungsi aktivasi ReLU dan dropout.
- Penggunaan fungsi aktivasi linear (activation='linear') pada lapisan keluaran.
- Penggantian metode optimasi menjadi 'sgd' (Stochastic Gradient Descent).
- Peningkatan jumlah epoch menjadi 200.

## Hasil plotting pada notebook:
![image](https://github.com/farreladelm/mikrokontroller-final-project/assets/72677417/38f9bb58-29a4-4206-b9a1-1feeca2391e7)
- Model deep learning berjalan dengan baik
- Kit tidak dapat melakukan peningkatan suhu secara signifikan melalui heater (27C --> 29C)

## Hasil pemantauan pada aplikasi MQTT Panel:
