# Acer-V14-Discord-Bot

## Uzmanlık Seviyesinde Discord Sunucu Yönetim ve Koruma Platformu

Acer-V14-Discord-Bot, Discord sunucuları için geliştirilmiş kapsamlı moderasyon, koruma ve yönetim sistemidir. 6 özelleşmiş bot mimarisi üzerinden çalışan bu platform, sunucunuzun güvenliğini, organizasyonunu ve aktivitesini uzman seviyesinde özelliklerle yönetir.

**Satın alım ve bizle irtibat için bize ulaşabilirsiniz:**
- [GutsV Discord](https://discord.gg/s93rTvJg98)
- [Telegram](https://t.me/projectgutsv)

**Geliştirici:** Acer  
**Geliştirme Ekibi:** GutsV

---

## ⚙️ Sistem Mimarisi

**Multi-Bot Architecture:** 6 özelleşmiş bot mimarisi ile çalışır. Management (Ana komut botu, ekonomi, oyun), Central (Sistem komutları, vanity URL koruma, chat guard), Punisher (Ceza otomasyonu), Closer (Guard event yakalama), Revert (Geri alma sistemi), Logger (Kapsamlı loglama). Her bot kendi uzmanlık alanında optimize edilmiş performans sunar.

---

## 🛡️ Koruma Sistemleri

### Vanity URL Guard & Protection

Sunucunuzun vanity URL'si, dijital kimliğinizin kritik bir parçasıdır. Guard Mode ile gerçek zamanlı izleme (Discord Gateway WebSocket üzerinden saniyeler içinde tespit), anında müdahale (otomatik geri yükleme, MFA token entegrasyonu, 5 kez otomatik yeniden deneme), MFA token yönetimi (otomatik ticket alma ve token üretme, güvenli saklama, 5 dakikalık yenileme döngüsü), rate limit yönetimi (proaktif kontrol ve otomatik bekleme), webhook bildirimleri (anlık durum bildirimi), TLS güvenli iletişim (Discord Canary API'ye doğrudan bağlantı).

### Guard Systems

**Sunucu, Rol, Kanal, Emoji, Sticker, Bot, Ban/Kick Koruması** - Yetkisiz değişiklikleri engelleme, audit log entegrasyonu, otomatik yedekleme ve geri yükleme.

**Chat Protection** - Küfür, reklam, capslock, spam ve invite link koruması. Özelleştirilebilir filtreler, otomatik mesaj silme ve kullanıcı uyarı sistemi.

---

## ⚖️ Moderasyon Özellikleri

**Ceza Sistemi** - Ban, Kick, Mute, Voice Mute, Jail, Timeout, Warn. Süre bazlı otomatik takip, ceza bitişi kontrolü, geçmiş ve istatistikler, ceza puanı sistemi, toplu işlemler.

**Kayıt Sistemi** - Erkek/Kadın kayıt (özelleştirilebilir komutlar, yaş doğrulama), kayıtsız yönetimi (otomatik rol verme/alma, kanal erişim kontrolü), hoşgeldin sistemi (özelleştirilebilir mesajlar, embed formatı).

**Tag Sistemi ve GutsV API Entegrasyonu** - GutsV API üzerinden otomatik tag tarama (sunucu tagı, bio, pronouns, username, display name, presence kontrolü), otomatik rol verme/alma, nickname güncelleme, tag istatistikleri. Founding roles onay mekanizması, button-based approval, özelleştirilebilir ayarlar (tag modu, private mod, banned tag yönetimi).

---

## 💰 Ekonomi ve Oyun Sistemleri

**Ekonomi Sistemi** - Coin (Jeton) ve Gold (Altın) para birimleri. Mesaj, ses, davet, kayıt, tag verme, auth yapma ile para kazanma (ayarlanabilir miktarlar), günlük ödül sistemi, kullanıcılar arası transfer (geçmiş takibi, doğrulama, limit kontrolü).

**Oyun Sistemi** - İlk Yazan, Matematik, Kasa Bul, Tahmin, Memleket, Ülke Başkent, Blackjack, Coinflip, Slot, Rock Paper Scissors. 25 dakikada bir otomatik rastgele oyun, aktif sohbet kontrolü, canvas tabanlı profesyonel görseller.

**Mağaza Sistemi** - Item, Role, Badge satın alma. Özelleştirilebilir ürünler, stok yönetimi, kategorilendirme.

---

## 📊 İstatistik ve Yetkili Yönetim Sistemi

**Kullanıcı İstatistikleri** - Mesaj (toplam, haftalık, günlük, kanal bazlı), Ses (toplam süre, haftalık, günlük, kanal bazlı), Kamera ve Stream (toplam, haftalık, günlük süreler).

**Yetkili İstatistikleri (UpStaff)** - Görev Sistemi (oluşturma, atama, takip, coin ödülleri), Sorumluluk Sistemi (oluşturma, atama, tamamlama takibi), Auth ve Tag Sistemi (istatistikler, kalite skorlama, performans metrikleri), Rank Sistemi (coin bazlı yükseltme, otomatik rank rolü verme, section bazlı yönetim).

**Leaderboard Sistemleri** - Mesaj, Ses ve Tweet leaderboard'ları (top sıralamalar, haftalık/günlük listeler, kanal bazlı sıralamalar).

**Profil ve Kart Sistemi** - Canvas tabanlı profil kartları, istatistik görselleştirme, özelleştirilebilir tema, badge ve rozet gösterimi, detaylı kullanıcı bilgileri.

---

## 🚀 İleri Seviye Özellikler

**Özel Oda, Ticket, Toplantı, İtiraf, Giveaway, Tweet, Menü Sistemleri** - Özel oda oluşturma ve yönetimi, button-based ticket sistemi, toplantı başlatma ve katılımcı takibi, anonim itiraf kanalı, çekiliş yönetimi, Twitter benzeri mesajlaşma, özelleştirilebilir select menüler.

---

## 🔒 Güvenlik ve Yedekleme

**Otomatik Yedekleme** - Kanal yedekleme (metin, ses, kategori, permission overwrite), rol yedekleme (rol bilgileri, üye listesi, permission yedekleme), her saat otomatik yedekleme, seçici ve tarih bazlı geri yükleme.

**Whitelist Sistemi** - Full yetki listesi, rol/kanal/emoji/URL yönetim yetkileri, anlık işlem limiti, limit aşımı tespiti ve otomatik cezalandırma.

---

## 📝 Loglama ve İzleme

**Event Logging** - Kanal, rol, emoji, webhook, sticker, integration, event eventleri. Mesaj loglama (silme, düzenleme, snipe sistemi). Ses loglama (aktivite takibi, kanal değişiklikleri, spam kontrolü). Tüm event'ler detaylı şekilde kaydedilir.

---

## ⌨️ Komut Sistemi

**Moderation, Economy, Stat, Register, General, Owner Kategorileri** - Ban, kick, mute, jail, timeout, ceza kontrolü, bakiye görüntüleme, para transferi, istatistik görüntüleme, kayıt komutları, profil sistemleri, bot ayarları, özel komut oluşturma.

**Özel Komut Sistemi** - Talent Perms (rol bazlı yetkilendirme), özel komut oluşturma, komut izinleri (özelleştirilebilir yetkilendirme, çoklu rol desteği).

---

## 🔧 Teknik Özellikler

**MongoDB Entegrasyonu** - Kapsamlı şema yapısı, otomatik veri validasyonu, index ve query performans optimizasyonu.

**API Entegrasyonları** - GutsV API (kullanıcı profil bilgisi, tag kontrol, bio ve pronouns, real-time synchronization), Discord API (Gateway WebSocket, REST API, Audit Log, Voice API).

---

## ⚙️ Kurulum ve Yapılandırma

**Gereksinimler:** Node.js v16+, MongoDB veritabanı, minimum 4GB RAM, stable internet bağlantısı. Discord bot token'ları (6 bot için), MFA aktif Discord hesabı (Vanity URL guard için).

**Kurulum:**
1. Repository klonlama ve bağımlılıkları yükleme
2. MongoDB kurulumu ve bağlantı ayarları
3. Yapılandırma dosyasında gerekli ayarları yapma
4. Bot'ları başlatma

**Yapılandırma:**
Yapılandırma dosyasında bot token'ları, sunucu ID, MongoDB bağlantı string'i, MFA şifresi ve webhook URL'si gibi temel ayarları yapılandırmanız gerekmektedir. Örnek yapılandırma formatı:

```javascript
{
    Tokens: {
        // Bot token'ları
    },
    Guild: {
        ID: "SUNUCU_ID",
        Name: "SUNUCU_ADI"
    },
    Bot: {
        Prefixes: [".", "!", "?"],
        MongoURI: "mongodb://...",
        // Diğer ayarlar...
    }
}
```

---

## 📞 Destek ve Lisans

**Destek:** Issues, [GutsV](https://github.com/gutsv-project) veya [GutsV Discord](https://discord.gg/s93rTvJg98) üzerinden teknik destek alabilirsiniz. Detaylı hata logları ile birlikte sorunu bildirmeniz önerilir.

**Lisans:** MIT License

---
