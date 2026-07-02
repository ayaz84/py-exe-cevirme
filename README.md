# 🐍 Py → EXE Çevirme Aracı

Python `.py` dosyalarını kolayca `.exe` formatına dönüştürün. PyInstaller ve Nuitka destekli, sade arayüzlü bir Windows masaüstü uygulaması.

<br>

## 📸 Ekran Görüntüsü

> *(<img width="898" height="997" alt="Ekran görüntüsü 2026-07-02 111224" src="https://github.com/user-attachments/assets/af3633dc-1a96-4730-adb2-29bb83b2fc3a" />)*

<br>

## ✨ Özellikler

- 🔧 **İki Derleyici Desteği** — PyInstaller veya Nuitka seçeneği
- 📦 **Tek Dosya / Klasör** — `--onefile` veya standart çıktı
- 🖼️ **İkon Desteği** — `.ico`, `.png`, `.jpg` formatları desteklenir, otomatik dönüştürülür
- 📁 **Ek Dosya / Klasör** — Projeyle birlikte gömülecek dosyaları ekleyin
- 📋 **Kütüphane Tarayıcı** — `requirements.txt` otomatik algılanır ve kurulur
- 🏷️ **Versiyon Bilgisi** — Uygulama adı, sürüm, dosya açıklaması, telif hakkı
- 🗜️ **UPX Sıkıştırma** — Daha küçük EXE boyutu *(Sadece PyInstaller)*
- ⚡ **LTO Optimizasyonu** — Daha hızlı çalışan EXE *(Sadece Nuitka)*
- 🌙 **Karanlık / Aydınlık Tema** — Göz yormayan arayüz
- 🔄 **Otomatik Güncelleme** — GitHub Releases üzerinden güncelleme kontrolü
- 📊 **Canlı Log Paneli** — Derleme sürecini anlık takip edin

<br>

## 💻 Gereksinimler

- Windows 10 / 11
- Python 3.8+
- PyInstaller ve/veya Nuitka (kurulu değilse araç yönlendirir)

<br>

## 🚀 Kullanım

1. **Python Dosyası** kısmından `.py` dosyanızı seçin
2. İsterseniz **Çıktı Klasörü** ve **İkon** ekleyin
3. **Derleme Ayarları**nı yapılandırın (tek dosya, konsol, UPX vb.)
4. **Versiyon Bilgisi** kısmını doldurun *(isteğe bağlı)*
5. **EXE OLUŞTUR** butonuna tıklayın
6. Derleme tamamlandığında EXE belirttiğiniz klasöre çıkar (varsayılan: Masaüstü)

<br>

## ⚙️ Derleme Ayarları

| Ayar | Açıklama |
|------|----------|
| **Tek Dosya** | Tüm bağımlılıkları tek bir `.exe` içine gömer |
| **Konsolu Göster** | EXE çalışırken CMD penceresini gösterir/gizler |
| **İkon Kullan** | Seçilen ikonu EXE'ye uygular |
| **UPX Sıkıştırma** | EXE boyutunu küçültür *(PyInstaller)* |
| **LTO Optimizasyonu** | Bağlantı zamanı optimizasyonu *(Nuitka)* |

<br>

## 📥 İndirme

En son sürümü [**Releases**](https://github.com/ayaz84/py-exe-cevirme/releases/latest) sayfasından indirebilirsiniz.

<br>

## 🔄 Güncelleme

Uygulama açıldığında GitHub üzerinden otomatik güncelleme kontrolü yapar. Yeni sürüm bulunduğunda bildirim gösterilir ve tek tıkla güncelleme yapılır.

<br>

## 📝 Sürüm Notları


### v1.0.0
- İlk GitHub sürümü

<br>

## 👤 Geliştirici

**FurkanY** — [GitHub](https://github.com/ayaz84)

<br>

## 📄 Lisans

Bu proje kişisel kullanım amaçlıdır.
