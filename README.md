
### Penjelasan Singkat:
Script ini merupakan **simulasi robot DDMR** dengan dua mode skenario:
![image](https://github.com/user-attachments/assets/adcc7dc5-2770-40b9-8804-923870eb6950)

1. **Skenario Statis:**  
   Pengguna diminta mengklik untuk menempatkan 1-3 obstacle tetap.
   ![image](https://github.com/user-attachments/assets/9eecd3cc-0cce-4438-826f-4efdd0c79982)

3. **Skenario Dinamis:**  
   Obstacle bergerak dengan arah acak yang diperbarui tiap iterasi.

### Fitur Utama:
- **Kombinasi Pure Pursuit & Vector Field Histogram (VFH):**  
  - Pure Pursuit untuk menuju target.
  - VFH untuk menghindari obstacle dengan menganalisis sektor-sektor lingkungan.

- **Sensor Virtual:**  
  Memanfaatkan beam untuk mendeteksi jarak ke obstacle, ditampilkan sebagai garis merah putus-putus.

- **Kolisi dan Penghindaran:**  
  - Saat sektor tertentu menunjukkan kemungkinan tabrakan, robot menghindar dengan memutar arah.
  - Memprioritaskan belokan menjauhi arah bahaya.

- **Visualisasi Real-Time:**  
  - Robot (ikon hijau), target (biru), dan obstacle (ungu).
  - Teks arah untuk obstacle dinamis.
  - Panah arah robot.

---
https://youtu.be/KuXlSHayHlc?si=uTOTHReaV_KmARpm
