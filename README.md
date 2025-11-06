# Tugas-Akhir-2_Jarkom
Berdasarkan hasil pengujian menggunakan perintah ping terhadap alamat IP 192.168.0.3, terlihat bahwa konektivitas jaringan tidak stabil pada awal percobaan. Beberapa ping pertama mengalami request timed out, yang berarti tidak ada respons dari host tujuan. Namun, pada percobaan selanjutnya koneksi mulai stabil dengan hasil ping berhasil seluruhnya tanpa kehilangan paket. Hal ini menunjukkan bahwa jaringan memerlukan waktu untuk berinisialisasi sebelum dapat berfungsi dengan baik.

Ketidakstabilan tersebut dapat disebabkan oleh beberapa faktor, seperti perangkat yang belum sepenuhnya aktif, koneksi fisik yang belum stabil, atau perbedaan konfigurasi IP dan subnet mask antara perangkat pengirim dan penerima. Selain itu, kegagalan pada ping awal juga bisa terjadi karena proses Address Resolution Protocol (ARP) yang masih mencari alamat fisik (MAC address) dari IP tujuan. Setelah ARP cache terbentuk, koneksi berikutnya dapat berjalan normal.

https://youtu.be/O48kSSECeNA?si=75bj023XfXhSZlnd
