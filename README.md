# warband-mod-translator-turkce
Mount &amp; Blade: Warband modları için geliştirilmiş, oyun içi ID'leri koruyan ve Türkçe karakterleri font uyumlu hale getiren akıllı çeviri aracı.

# ⚔️ Warband Akıllı Mod Çevirici (v1.0)

Bu araç, **Mount & Blade: Warband** mod dosyalarını (.csv ve .txt) otomatik olarak Türkçeye çevirmek ve oyunun font yapısıyla (dds) uyumlu hale getirmek için geliştirilmiştir. 



### ✨ Özellikler
* **Akıllı Dil Algılama:** Zaten Türkçe olan satırları atlayarak internet kotasını korur ve çeviriyi hızlandırır.
* **ID Koruma:** Satır başındaki oyun içi kodlara (`str_example|`) asla dokunmaz, sadece mesaj kısmını çevirir.
* **Font Uyumu (Ascii-fying):** Oyun fontunun desteklemediği `ş, ğ, ç, İ` gibi harfleri otomatik olarak `s, g, c, I` harflerine dönüştürür.
* **Değişken Koruması:** Cümle içindeki `{s1}`, `{reg0}` gibi oyun değişkenlerini maskeler ve bozulmalarını önler.
* **Görsel Arayüz:** Terminal ile uğraşmadan, tek tıkla dosya seçip işlem yapmanızı sağlar.

### 🚀 Nasıl Kullanılır?
1. `Releases` kısmından güncel `.exe` dosyasını indirin.
2. Programı çalıştırın ve "Dosya Seç ve Çevir" butonuna basın.
3. Çevirmek istediğiniz mod dosyasını (örneğin `dialogs.csv`) seçin.
4. Program aynı klasörde `translated_` ön ekiyle yeni dosyanızı oluşturacaktır.

### 🛠️ Teknolojiler
- **Dil:** Python
- **Kütüphaneler:** `deep-translator`, `tkinter`, `re` (Regex)
- **Mimari:** Kullanıcı tarafından tasarlanan algoritma, yapay zeka desteği ile koda dökülmüştür.

### 📜 Lisans
Bu proje **MIT Lisansı** ile korunmaktadır. İstediğiniz gibi geliştirip paylaşabilirsiniz.

---
**Geliştirici:** JoelMiller46

