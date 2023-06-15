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
<img src="https://github.com/farreladelm/mikrokontroller-final-project/assets/72677417/3373437d-6bff-4b48-a7d6-67407a797fff" width="100">
![2](https://github.com/farreladelm/mikrokontroller-final-project/assets/72677417/e5988de1-14c8-4496-8c73-9410d015c0fa)
![3](https://github.com/farreladelm/mikrokontroller-final-project/assets/72677417/ce04736f-5c09-46f2-b3d4-a9062e79ae61)
![4](https://github.com/farreladelm/mikrokontroller-final-project/assets/72677417/2cf11555-198e-4a94-8574-d8570c66280b)

