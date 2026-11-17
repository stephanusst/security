Cara test di wokwi

1. Tekan Tombol SOS di NODE.
   - NODE: Kirim 3x, buzzer TIT TIT terus, TAPI Core 0 tetap bisa terima.
2. Tekan Tombol SOS di NODE lagi, sambil buzzer masih bunyi.
   - Harus langsung kirim lagi, tidak nunggu buzzer berhenti.
   - Kalau versi lama, harus nunggu buzzer berhenti dulu.
3. Tekan 2 tombol bareng di 2 NODE (kalau Bapak buat 2 NODE).
   - 2 SOS masuk antrean, tidak ada yang hilang, tidak ada yang tabrakan.
   - REPEATER: Delay acak 10-120ms, kirim 1x, tidak dobel.
4. SERVER terima, TTS, kirim ACK, NODE berhenti bunyi.



Kalau di wokwi tidak jalan, di atasnya tambahkan ini

#include <esp_wifi.h>