# C. ADC (Analog to Digital Converter) dan DAC (Digital to Analog Converter)

## 1. Membaca Nilai Analog dari Potensiometer

### a. Rangkaian
Rangkaian pada percobaan ini adalah sebagai berikut

![rangkaian](https://github.com/FerdyRino/Embedded/assets/151800680/31f78c40-6aa0-4445-b94f-9a00d5d1b34f)


### b. Code

![c-1](https://github.com/FerdyRino/Embedded/assets/151800680/e6ce4e83-17fa-42bf-b9b0-3742c8f64760)


### c. Hasil dan Pembahasan
Percobaan ini melibatkan pembacaan nilai potensiometer yang terhubung ke pin GPIO 34 (ADC1_CH6) pada platform ESP32. Setiap 500 milidetik, nilai potensiometer dibaca dan kemudian dicetak ke Serial Monitor. Output yang terlihat pada Serial Monitor berupa deretan nilai-nilai potensiometer yang berkisar antara 0 hingga 4095, mengingat bahwa ADC pada ESP32 memiliki resolusi sebesar 12-bit.




https://github.com/FerdyRino/Embedded/assets/151800680/84287f3f-eba5-4d2a-b853-91d4a1e71460




## 2. ADC dan DAC | Mengatur Kecerahan LED Menggunakan Potensiometer

### a. Langkah
Buatlagh program dengan menambahkan LED pada GPIO 5, kemudian putar potensiometer dari nilai terendah hingga 
nilai tertinggi. Amati yang terjadi, analisis dan dokumentasikan hasilnya.



### b. Code

![c-2](https://github.com/FerdyRino/Embedded/assets/151800680/ed1c4553-ad7c-4161-9680-c9a4f91390a5)


### c. Hasil dan Pembahasan
Program ini memiliki dua output utama yang ditampilkan pada Serial Monitor. Pertama, nilai pembacaan dari potensiometer (sensorValue) yang berkisar antara 0 hingga 4095 karena resolusi ADC pada ESP32 adalah 12-bit. Kedua, nilai keluaran yang diatur pada LED menggunakan PWM (outputValue), yang telah dipetakan ke rentang 0 hingga 255


https://github.com/FerdyRino/Embedded/assets/151800680/40419a32-309e-459b-840d-bc8625236486



