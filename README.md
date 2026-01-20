# İhbar Süresi Hesaplama Aracı

Personel çıkışlarında ihbar süresini ve son çalışma gününü hesaplayan İnsan Kaynakları uygulaması.

## 🎯 Özellikler

- ✅ **İş Kanunu Uyumlu**: 4857 sayılı İş Kanunu'na göre otomatik ihbar süresi hesaplama
- ✅ **İş Arama İzni**: Toplu kullanım desteği ile otomatik hesaplama
- ✅ **Akıllı Tarih Sistemi**: Hafta sonları ve resmi tatilleri otomatik atlar
- ✅ **Mobil Uyumlu**: Responsive tasarım, her cihazda kullanılabilir
- ✅ **Kullanıcı Dostu**: Sade ve anlaşılır arayüz

## 📋 İhbar Süreleri

Kıdem süresine göre yasal ihbar süreleri:

| Kıdem Süresi | İhbar Süresi |
|-------------|-------------|
| 6 aydan az | 2 hafta |
| 6 ay - 1.5 yıl | 4 hafta |
| 1.5 - 3 yıl | 6 hafta |
| 3+ yıl | 8 hafta |

## 🚀 Kullanım

1. **İşe Başlama Tarihi**: Çalışanın işe başladığı tarihi seçin
2. **Çıkış Bildirimi Tarihi**: İstifa/bildirim yapıldığı tarihi seçin
3. **İş Arama İzni**: İsterseniz toplu kullanım seçeneğini aktifleştirin
4. **Hesapla**: Sonuçları görüntüleyin

### İş Arama İzni Hesaplama

- İhbar süresi boyunca günlük **2 saat** iş arama izni hakkı vardır
- Sadece **iş günleri** (Pazartesi-Cuma) için hesaplanır
- Toplu kullanımda günlük çalışma saatine bölünür
- **0.5 ve üzeri yukarı**, altı aşağı yuvarlanır

**Örnek:**
- 2 hafta ihbar süresi = 14 takvim günü
- Bu süre içinde 10 iş günü var
- 10 gün × 2 saat = 20 saat iş arama izni
- 20 saat ÷ 9 saat/gün = 2.22 → **2 gün** (aşağı yuvarlandı)
- Son çalışma günü: 14 - 2 = **12. gün**

## 🛠️ Teknolojiler

- **React 18**: Modern kullanıcı arayüzü
- **Tailwind CSS**: Responsive tasarım
- **Vanilla JavaScript**: Bağımlılık yok, hızlı çalışır

## 📦 Kurulum

### 1. GitHub'dan İndirme

```bash
git clone https://github.com/kullaniciadi/ihbar-suresi-hesaplama.git
cd ihbar-suresi-hesaplama
```

### 2. Çalıştırma

Basitçe `index.html` dosyasını tarayıcınızda açın.

### 3. GitHub Pages ile Yayınlama

1. Repository'yi GitHub'a yükleyin
2. Settings > Pages bölümüne gidin
3. Source olarak `main` branch'i seçin
4. Save'e tıklayın
5. Birkaç dakika içinde `https://kullaniciadi.github.io/ihbar-suresi-hesaplama` adresinde yayında olacak

## 🌐 Canlı Demo

[Demo Linki](https://kullaniciadi.github.io/ihbar-suresi-hesaplama)

## 📱 PWA - Mobil Uygulama Gibi Kullanım

Telefonunuzdan:
1. Tarayıcıda açın
2. Menüden "Ana ekrana ekle" seçeneğini tıklayın
3. Artık uygulama gibi kullanabilirsiniz

## 🤝 Katkıda Bulunma

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/yeni-ozellik`)
3. Commit yapın (`git commit -m 'Yeni özellik eklendi'`)
4. Push yapın (`git push origin feature/yeni-ozellik`)
5. Pull Request açın

## 📝 Lisans

MIT License - Detaylar için [LICENSE](LICENSE) dosyasına bakın

## 👨‍💼 Gelecek Özellikler

- [ ] Birden fazla personel için toplu hesaplama
- [ ] PDF rapor çıktısı
- [ ] Geçmiş hesaplamaları kaydetme
- [ ] Excel'den veri aktarma
- [ ] Kıdem tazminatı hesaplama
- [ ] Yıllık izin hesaplama

## 📧 İletişim

Sorularınız için issue açabilirsiniz.

---

**Not:** Bu uygulama bilgilendirme amaçlıdır. Yasal danışmanlık yerine geçmez.
