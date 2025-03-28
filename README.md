# Açık Kaynak İşletim Sistemi Projesi

## Hakkında
Bu proje, temel komut satırı becerilerini kullanarak dokümanlar oluşturma, düzenleme, birleştirme ve yetkilendirme işlemlerini nasıl gerçekleştirebileceğinizi göstermeyi amaçlar. 

## Örnek Görevler ve Çözümler

### Görev 1: "okul.txt" Dosyasının Oluşturulması
- **Amaç**: Masaüstünde "okul.txt" adında bir dosya oluşturmak, içerisine ad-soyad ve bölüm bilgilerini eklemek, kelime ve karakter sayısını bulmak.
- **Komutlar**:
  ```bash
  cd Masaüstü
  touch okul.txt
  echo "İsim Soyisim Bölüm" > okul.txt
  cat okul.txt
  wc -c okul.txt
  wc -w okul.txt
  
Görev 2: Dosyaların Birleştirilmesi
Amaç: "ben.txt" ve "program.txt" dosyalarını oluşturmak, içerik eklemek ve bu dosyaları birleştirerek "birleştirme.txt" oluşturmak.<br>
 
- **Komutlar**:
 
      *cd Masaüstü
      *touch ben.txt
      *echo "İsim Soyisim Memleket" > ben.txt
      *cat ben.txt
      *touch program.txt
      *echo "Python C++ HTML" > program.txt
      *paste ben.txt program.txt > birleştirme.txt
      *cat birleştirme.txt
      *mkdir komut
      *mv birleştirme.txt komut

Görev 3: Yetkilendirme<br>
Amaç: "yetki" adında bir dizin oluşturmak ve "yetkilendirme.txt" dosyasına grup ve diğer kullanıcılar için yazma yetkisi vermek.<br>


- **Komutlar**:
 
      *cd Masaüstü
      *mkdir yetki
      *cd yetki
      *touch yetkilendirme.txt
      *ls -l yetkilendirme.txt
      *chmod 640 yetkilendirme.txt
      *ls -l yetkilendirme.txt
      *cd Masaüstü
      *mkdir yetki
      *cd yetki
      *touch yetkilendirme.txt
      *ls -l yetkilendirme.txt
      *chmod 640 yetkilendirme.txt
      *ls -l yetkilendirme.txt

## Hakkında<br>
Bu dosya, açık kaynak işletim sistemi konusundaki ödev sorularını ve çözümlerini içermektedir. Çalışma komutların işlevlerini açıklayarak temel bilgileri pekiştirmeyi amaçlar.<br>
![WhatsApp Image 2025-03-28 at 15 23 50](https://github.com/user-attachments/assets/540ab101-bcc9-4c4d-9540-f5c548b4bf67)


### 1. Yukarıdaki görselde gerçekleşen komut adımlarını açıklayınız<br>
1. **Adım 1:** Masaüstüne gidildi.<br>
2. **Adım 2:** Yeni bir `Güvenlik` dökümanı oluşturuldu.<br>
3. **Adım 3:** Dosya içerikleri listelendi.<br>
4. **Adım 4:** `Güvenlik` dökümanına yeni veri eklendi, sonrasında `Ctrl-D` ile çıkış yapıldı.<br>
5. **Adım 5:** Dosyanın içeriği görüntülendi.<br>
6. **Adım 6:** Dosya üzerine yeni veri eklendi.<br>
7. **Adım 7:** Dosyanın son hali tekrar görüntülendi.<br>

---

### 2. `cat -n /etc/passwd` Komutunun İşlevi<br>
Bu komut, `passwd` dosyasındaki içerikleri sıralı bir şekilde numaralandırarak listeler.<br>

---



### 3. Komut Bloğu Çıktısı<br>
    **Komut Bloğu:**

    $ echo Açık Kaynak > ders1.txt
    $ echo İşletim Sistemi > ders2.txt
    $ cat ders1.txt ders2.txt
    
- **Ekran Çıktısı:**<br>
*Açık Kaynak<br>
*İşletim Sistemi<br>

### 4. "Deneme.txt" Dökümanındaki İlk İki Satır<br>
*100 satırlık paragraftan sadece ilk iki satırı görüntülemek için kullanılan komut:<br>
*more -n 2 Deneme.txt<br>

### 5. "passwd" Dökümanının İlk ve Son Beş Satırı
**İlk 5 Satır:**
*head -n 5 /etc/passwd

**Son 5 Satır:**
*tail -n 5 /etc/passwd




<br>
Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
