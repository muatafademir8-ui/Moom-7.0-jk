MOOM 6.2 - SILAH SESLERI EKLENMIS SURUM

SILAH SESLERI (kullanici tarafindan yuklenen videolardan ayiklandi):
- 1. dosya (1000072029.mp4): M249 ates sesi
- 2. dosya (1000072026.mp4): Pompalı tufek ates sesi
- 3. dosya (1000072023.mp4): Cift tabanca ates sesi

Sesler 22050 Hz, mono, 16-bit PCM olarak main.c icine gomuludur.
Oyunun yaninda ayri ses dosyasi tasimak gerekmez. Olum sesi de korunmustur.
R1 ile silah degistirme: pompalı -> cift tabanca -> M249.

DERLEME
main.c ve Makefile dosyalarini PSP SDK projenize koyup PSPSDK ile derleyin.

DOGRULAMA
Kaynak kodda ses verileri ve silah-ses eslestirmeleri kontrol edildi.
Bu ortamda PSP SDK bulunmadigindan EBOOT.PBP derlemesi ve PPSSPP/PSP testi yapilmadi.
PSP ses API'si sesleri tek kanalda sirayla calistirir; M249 atislarinda hizli tetiklenen
ses istekleri calan klip bitene kadar birlestirilebilir.
