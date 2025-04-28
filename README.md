# Arsitektur-Multiple-Prosesor-dan-Multiprosesor-Symmetric

![Untitled Diagram drawio](https://github.com/user-attachments/assets/8de222f0-f038-4205-8aed-c0c528fc1e9a)

diagram ini dibagi menjadi dua bagian utama:

1. multiprosesor symmetric

- ada satu main cpu yang terhubung langsung dengan memory dan i/o device.

- dari main cpu, terdapat koneksi ke beberapa sub cpu.

- setiap sub cpu juga memiliki akses ke memory sendiri.

- semua komponen ini saling terhubung melalui system bus.

- sistem ini menekankan bahwa semua prosesor berbagi memori dan perangkat input/output secara seimbang.

2. multiple prosesor

- di bagian ini, terdapat empat proses (process 1, process 2, process 3, process 4) yang masing-masing dihubungkan ke empat cpu (cpu 0, cpu 1, cpu 2, cpu 3).

- keempat cpu ini terhubung ke satu modul ram besar.

- arsitektur ini menggambarkan banyak proses yang didistribusikan ke beberapa cpu yang kemudian mengakses memori bersama.


KESIMPULAN:

- pada multiprosesor symmetric, semua cpu (termasuk main dan sub cpu) bekerja bersama-sama, berbagi memori dan perangkat i/o melalui satu jalur system bus. kerjanya seimbang, tidak ada cpu yang lebih tinggi atau lebih rendah.

- pada multiple prosesor, banyak cpu digunakan untuk menangani proses-proses berbeda, tapi tetap berbagi satu memori utama (ram). setiap cpu bisa menjalankan proses sendiri-sendiri. 
