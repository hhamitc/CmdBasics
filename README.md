# Windows için Basit Cmd Komutları

## Öğrenenler İçin Kontrol Listesi  

- [ ] Komut İstemini (cmd.exe) Açma
- [ ] Tüm Dizinleri/Dosyaları Listeleme
- [ ] Dizin Değiştirme
- [ ] Üst Dizine Çıkma
- [ ] Kök Dizine Gitme
- [ ] Dizin Oluşturma
- [ ] Metin Dosyası Oluşturma
- [ ] Metin Dosyasının İçeriğini Gösterme
- [ ] Dosya Silme
- [ ] Dizin Silme
- [ ] Konsol Ekranını Temizleme
- [ ] Konsoldan Çıkma
- [ ] ```TAB``` Tuşundan Yararlanma


## Örnekler
### Komut İstemini (Command Prompt) Açma
WIN + R (RUN/ÇALIŞTIR) > cmd [ENTER]\
ya da\
Başlat Menüsü > cmd [ENTER]

### dir - Directory
Mevcut dizinde (içinde bulunulan klasörde) yer alan tüm dosya ve dizinleri listeler.
```
dir
```

### cd - Change Directory
Mevcut dizini değiştirir.
```
C:\Users\Kullanici>cd desktop
C:\Users\Kullanici\Desktop>cd C:\Windows
C:\Windows>
```

### cd..
Bir üst dizine çıkar.
```
C:\Users\Kullanici\Desktop>cd..
C:\Users\Kullanici>
```

### cd\
Kök dizine gider.
```
C:\Users\Kullanici\Desktop>cd\
C:\>
```

### md - Make Directory
Dizin oluşturur.
```
md yazilarim
```

### echo
Girilen metni bir dosyaya kaydeder.
```
echo merhaba dünya > notlarım.txt
```

### more
Bir metin dosyasının içeriğini gösterir.
```
C:\Users\Kullanici\Desktop>more notlarım.txt
merhaba dünya
```

### del - delete
Adı/yolu verilen dosyayı siler.
```
del notlarım.txt
```

### rd - Remove Directory
Belirtilen dizini kaldırır.
```
rd çarşamba
```

### exit
Konsoldan çıkışı sağlar. (Konsol penceresini kapatır.)


### cls 
Konsol ekranını temizler.

> İPUCU: Konsol ekranında bir dosya adı ya da dizin adı yazarken ilk bir kaç harfini girdikten sonra ```TAB``` tuşuna basarsanız otomatik tamamlar.