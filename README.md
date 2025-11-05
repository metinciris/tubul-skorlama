# tubul-skorlama

NGS Gland/Tubule Scoring Helper

Bu proje, **Nottingham Grading System (NGS)** kapsamında glandüler/tübül formasyonunun (G/TF) değerlendirilmesini kolaylaştırmak için geliştirilmiş **interaktif HTML tabanlı bir yardımcı araçtır**.  
Patoloji uzmanları ve asistanlarının zor morfolojik desenlerde daha tutarlı skorlamalar yapmasına yardımcı olur.

---

## 🎯 Amaç
- G/TF tanımlamasındaki belirsizlikleri azaltmak.
- Genişletilmiş açıklamayı (cribriform, müsinöz, mikropapiller paternler dahil) pratik olarak kullanmak.
- Zor vakalarda hızlı karar destek aracı olarak kullanılmak.

---

## ⚙️ Özellikler
- ✅ **Tıklanabilir kriter seçimi:** Dahil ve hariç morfolojik özellikler interaktif olarak seçilir.
- 🎚️ **Oran seçici:** G/TF oranını sürgü veya hızlı yüzde tuşlarıyla seç.
- 📊 **Otomatik skor hesaplama:** 1–3 arası NGS puanı anında hesaplanır.
- 💾 **Kaydet / Yükle / Dışa Aktar:** Tarayıcıda saklama ve TXT olarak dışa aktarma.
- 📘 **Zor vaka ipuçları:** Her zaman görünür; özellikle cribriform, müsinöz ve mikropapiller desenlerde rehberlik sağlar.
- 🧬 **Mikroskopik tip listesi:** Literatürden özetlenmiş patern özellikleri.
- ☀️ **Açık tema:** Klinik ve laboratuvar ortamlarında okunabilirlik için optimize edilmiştir.

---

## 🧠 Kullanım
1. `index.html` dosyasını tarayıcıda aç.
2. İncelediğin tümör için uygun morfolojik kriterleri tıkla.
3. Tümördeki G/TF oranını sürgü veya hızlı tuşlarla belirle.
4. Sonuç alanında otomatik skor ve gerekçeyi gör.
5. Gerektiğinde **not ekle** ve **sonucu panoya kopyala** veya **TXT olarak dışa aktar**.

**Demo:** [Demo](https://metinciris.github.io/tubul-skorlama/)  

---

## 📚 Kaynak
Bu uygulama, aşağıdaki çalışmanın bulgularına dayanır:
> Karakas C, Aldrees R, Mohamed A, et al. *A Validation Study of an Expanded Description of Glandular (Acinar)/Tubule Formation for the Use of the Nottingham Grading System for Invasive Breast Carcinomas*. **Arch Pathol Lab Med.** 2025; doi:10.5858/arpa.2025-0280-OA.

---

## 🧩 Dosya Yapısı
```
├── index.html          # Ana interaktif araç (tek dosya)
├── README.md           # Bu belge
```

---

## 🚀 Yayınlama
Bu proje tamamen istemci tarafında çalışır, herhangi bir sunucu gerektirmez.
GitHub Pages üzerinde yayımlamak için:
1. Depoyu oluştur.
2. `index.html` ve `README.md` dosyalarını ekle.
3. GitHub Pages’i **main** dalından etkinleştir.
4. Tarayıcıdan uygulamayı aç: `https://<kullanıcı_adı>.github.io/<repo_adı>/`

---

## 🧑‍⚕️ Geliştirici Notu
Bu araç, patologlar için eğitim ve standartlaştırma amaçlıdır.  
Klinik karar destek sistemi değildir, ancak **rehber materyal** olarak kullanılabilir.

---

**Lisans:** MIT  

**Yıl:** 2025
