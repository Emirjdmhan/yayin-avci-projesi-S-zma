# 📡 Yayıncı Avı Projesi

Bu projede, **Wireshark** kullanarak YouTube üzerinde bir **canlı yayın izlenirken** ağ trafiği analiz edilmiştir. Özellikle **HTTPS (TCP port 443)** üzerinden geçen veri paketleri incelenmiş ve `.pcapng` formatında kaydedilmiştir.

---

## 🎯 Amaç

- Yayın sırasında kullanılan **IP adreslerini** ve **portları** tespit etmek  
- Gerçek zamanlı ağ trafiğini **Wireshark** ile kaydetmek  
- Yapılan analizleri **.pcapng** ve görsel formatta dokümante etmek

---

## 🛠️ Kullanılan Araçlar

- 🐬 **Wireshark** – Ağ trafiği yakalama ve analiz  
- 📺 **YouTube** – Canlı yayın kaynağı  
- 🧠 **GitHub** – Proje sunumu ve raporlama

---

## 🧪 İçerik

- `trafik.pcapng` → YouTube canlı yayını izlenirken kaydedilen ağ trafiği
- `Ekran Görüntüsü.png` → Wireshark ekranından alınan analiz anı görüntüsü

---

## 🖼️ Örnek Görsel

Aşağıda analiz sırasında alınan ekran görüntüsü yer almaktadır:

![Wireshark Analizi](Ekran%20Görüntüsü.png)

---

## 🔍 Teknik Detaylar

- **Filtre:** `tcp.port == 443`  
- **Protokoller:** TCP, TLSv1.2  
- **Format:** `.pcapng` (Wireshark varsayılan kayıt biçimi)  
- **Veri:** Şifreli HTTPS trafiği, analiz sadece meta-veri seviyesindedir (içerik okunmaz)

---

## 👨‍💻 Geliştirici

- **Ad Soyad:** Emirhan Akdoğan  
- **Öğrenci No:** 222 019 042  
- **GitHub Kullanıcı Adı:** [Emirjdmhan](https://github.com/Emirjdmhan)  
- **Proje Linki:** [yayın-avcı-projesi-S-zma](https://github.com/Emirjdmhan/yayin-avci-projesi-S-zma)

---

## 👥 Takım Bilgisi

> Bu proje bireysel olarak gerçekleştirilmiştir ve sadece Emirhan Akdoğan'a aittir.

---

## ✅ Sonuç

Proje kapsamında YouTube canlı yayını sırasında oluşan ağ trafiği başarıyla analiz edilmiştir. Veri içeriği şifreli olmasına rağmen bağlantı noktaları, IP adresleri ve protokol bilgileri incelenerek **canlı yayın trafiğinin izi sürülmüştür**.

