# WHOIS Alan Adı Sorgulama Aracı 🔍

<p align="center">
  <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?w=800&q=80" alt="WHOIS Alan Adı Sorgulama" width="600">
</p>

## 📋 Genel Bakış

WHOIS Alan Adı Sorgulama Aracı, herhangi bir alan adının kayıt bilgilerini, bitiş tarihini ve daha fazlasını anında öğrenmenizi sağlayan modern bir web uygulamasıdır. Kullanıcı dostu arayüzü ve kapsamlı bilgi sunumu ile alan adı yönetimi için mükemmel bir araçtır.

## ✨ Özellikler

- **Kapsamlı WHOIS Bilgisi**: Alan adı kayıt tarihi, bitiş tarihi ve kayıt şirketi bilgilerine anında erişim
- **Bitiş Tarihi Takibi**: Alan adının bitiş tarihine kalan gün sayısını otomatik hesaplama
- **Türkçe Arayüz**: Tamamen Türkçe kullanıcı deneyimi
- **Karanlık Mod**: Göz yorgunluğunu azaltan karanlık mod desteği
- **Responsive Tasarım**: Mobil cihazlar dahil tüm ekran boyutlarına uyumlu tasarım
- **Kolay Kopyalama**: Tam WHOIS verisini tek tıklamayla kopyalama özelliği
- **IP Adresi Gösterimi**: Kullanıcının IP adresini otomatik tespit etme ve gösterme
- **.tr Alan Adları Desteği**: Türkiye alan adları için özel destek

## 🚀 Demo

Canlı demo: [WHOIS Alan Adı Sorgulama Aracı](https://whois-domain-lookup.vercel.app)

## 🛠️ Teknolojiler

- **Frontend**: React, TypeScript, Tailwind CSS
- **UI Bileşenleri**: Shadcn UI
- **Form Yönetimi**: React Hook Form, Zod
- **API**: WhoisXML API

## 📱 Ekran Görüntüleri

<p align="center">
  <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=800&q=80" alt="Ana Sayfa" width="400">
  <img src="https://images.unsplash.com/photo-1555066932-e78dd8fb77bb?w=800&q=80" alt="Sonuçlar" width="400">
</p>

## 🔧 Kurulum ve Kullanım

1. Repoyu klonlayın:
   ```bash
   git clone https://github.com/PayizTV/whois-domain-lookup.git
   ```

2. Bağımlılıkları yükleyin:
   ```bash
   cd whois-domain-lookup
   npm install
   ```

3. Geliştirme sunucusunu başlatın:
   ```bash
   npm run dev
   ```

4. Tarayıcınızda açın:
   ```
   http://localhost:5173
   ```

## 🔑 API Anahtarı

Uygulama WhoisXML API kullanmaktadır. Kendi API anahtarınızı kullanmak için `src/lib/whoisApi.ts` dosyasındaki `API_KEY` değişkenini güncelleyin.

## 📝 Nasıl Kullanılır

1. Ana sayfadaki arama kutusuna sorgulamak istediğiniz alan adını girin (örn. example.com)
2. "Alan Adı Sorgula" butonuna tıklayın
3. Sonuçlar otomatik olarak aşağıda görüntülenecektir
4. Tam WHOIS verisini kopyalamak için "Kopyala" butonunu kullanabilirsiniz

## 🌐 Desteklenen Alan Adları

Uygulama tüm TLD'leri (Top Level Domain) desteklemektedir, özellikle:
- .com, .net, .org gibi genel alan adları
- .com.tr, .org.tr, .edu.tr gibi Türkiye alan adları
- .io, .dev, .app gibi yeni nesil alan adları

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Lütfen bir pull request göndermeden önce değişikliklerinizi tartışmak için bir issue açın.

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakın.

## 📞 İletişim

Sorularınız veya geri bildirimleriniz için [issues](https://github.com/PayizTV/whois-domain-lookup/issues) sayfasını kullanabilirsiniz.

---

<p align="center">
  Developed with ❤️ by <a href="https://github.com/PayizTV">PayizTV</a>
</p>
