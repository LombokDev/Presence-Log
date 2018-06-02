# Presence-Log
Log kehadiran peserta dari QRCode

## Komponen utama
Komponen utama aplikasi ini adalah:
1. Kegiatan
2. Sesi presensi
2. Presensi store

**Kegiatan** adalah kegiatan yang akan dilaksanakan, setiap kegiatan yang akan dilaksanakan akan memiliki **Sesi presensi**. **Sesi presensi** adalah sesi dimana presensi akan disimpan, setiap kegiatan bisa memiliki lebih dari satu **sesi presensi** misal "Sesi registrasi datang", "Sesi registrasi masuk kelas", "Sesi pengambilan makan". **Presensi store** adalah data yang disimpan kedalam **sesi presensi**, **presensi store** akan menjadi repositori dari **sesi presensi**, **presensi store** bisa dimanfaatkan untuk validasi apakah peserta sudah melakukan log presensi sebelumnya atau tidak pada **sesi presensi**



## Workflow
1. Membat **Kegiatan**
2. Menambahkan **Sesi presensi** pada **Kegiatan yang dibuat**
3. Melakukan scan terhadap peserta melalu QRCode pada **Sesi presensi** yang dipilih
