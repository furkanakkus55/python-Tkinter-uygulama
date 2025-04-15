# 🧾 Kişisel Bilgi Kayıt Uygulaması (Python - Tkinter)
Bu proje, Python'un yerleşik GUI kütüphanesi olan tkinter kullanılarak geliştirilmiş, kullanıcıdan kişisel bilgiler toplayan ve bu bilgileri grafik arayüz üzerinde yönetebilen bir masaüstü uygulamasıdır. Amaç, kullanıcı dostu bir arayüzle temel Python nesne tabanlı programlama (OOP) ve arayüz (GUI) becerilerini birleştiren, hem öğretici hem de işlevsel bir örnek sunmaktır.

Uygulama, kullanıcıdan isim, soyisim, yaş, boy, ülke, e-posta, telefon ve ilgi alanları gibi bilgileri alır ve bunları ekranda gösterebilir ya da güncelleyebilir. Bilgiler, bir Kisi sınıfı içerisinde tutulur ve bu sınıfın metotları aracılığıyla yönetilir.

Bu proje; başlangıç seviyesinden orta seviyeye geçiş yapan, hem tkinter GUI geliştirmeyi öğrenmek isteyen hem de OOP mantığını pratiğe dökmek isteyen herkes için idealdir. Aynı zamanda küçük çaplı masaüstü yazılım geliştirme projelerine ilk adımı atmak için de güzel bir örnektir.

Öğrenciler için ödev, geliştiriciler için temel GUI alıştırması, kariyer yolculuğuna başlayanlar için ise portföy projesi olarak kullanılabilir.


---

##  İçerik

- [Özellikler](#-özellikler)
- [Gereksinimler](#-gereksinimler)
- [Nasıl Çalıştırılır](#-nasıl-çalıştırılır)
- [Kullanım Detayları](#-kullanım-detayları)
- [Ekran Görüntüsü (isteğe bağlı)](#-ekran-görüntüsü)
- [Geliştirici](#-geliştirici)

---

##  Özellikler

--- Kullanıcıdan şu bilgileri alır:

- İsim  
- Soyisim  
- Yaş  
- Boy  
- Ülke  
- E-posta  
- Telefon  
- İlgi Alanları (virgülle ayrılmalı)

--- Arayüz üzerinde:

- Bilgi güncelleme
- Bilgi gösterme
- Bilgi girilmeden işlem yapılmak istenirse uyarı

--- `messagebox` ile bilgilendirme ve hata mesajları

---

##  Gereksinimler

- Python 3.x (Önerilen: 3.8+)
- `tkinter` modülü *(Python ile birlikte gelir, ayrıca kurulmaz)*

---

##  Nasıl Çalıştırılır

1. Python yüklü olduğundan emin ol.
2. Bu repoyu klonla veya `.py` dosyasını bilgisayarına kaydet:
    ```bash
    git clone https://github.com/kullaniciadi/proje-adi.git
    ```
3. Terminalden proje klasörüne gir:
    ```bash
    cd proje-adi
    ```
4. Uygulamayı başlat:
    ```bash
    python kisi_kayit.py
    ```

 **Not:**  
Uygulamada şu satır var:
```python
self.iconbitmap("ikonum.ico")
