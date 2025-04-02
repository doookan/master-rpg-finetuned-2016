# Safir Roleplay - Fine-Tuned Mod (2016)

Bu mod, 2016 yılında çeşitli SA:MP Roleplay altyapılarının harmanlanması ve zamanla birçok düzenleme (fine-tuning) yapılması ile oluşturulmuştur. PAWN diliyle yazılmıştır.

## ✨ Özellikler

- Kayıt / Giriş sistemi (MySQL destekli)
- Meslekler, iş sistemleri (Dedektif, Taksi, Pizza, Tır, vb.)
- Admin panel ve yetkilendirme sistemi
- Ev, araç, kilit, anahtar sistemleri
- Uyuşturucu, eskort, boks gibi detaylı yan sistemler
- Boombox, radyo stream, müzik sistemi
- MDC (polis bilgisayarı), cezalandırma ve oyuncu yönetimi
- Çok sayıda tanımlı renk, TextDraw, 3DText sistemi
- Anti-cheat ve flood koruma gibi temel güvenlik sistemleri
- Sıfırdan yazılmamış; ancak birçok modül optimize edilmiştir.

## ⚠️ Not

Bu mod tamamen sıfırdan yazılmamıştır. Çeşitli açık kaynaklı RP altyapıları temel alınmış, zaman içinde düzenlenmiş ve modifiye edilmiştir. Paylaşım amacı nostalji ve arşiv değeridir.

## 🛠 Kurulum

1. `gamemodes/mymod.pwn` dosyasını sunucu dizinine atın.
2. `include/`, `filterscripts/`, `plugins/` klasörlerini uygun içerikle doldurun.
3. `server.cfg` dosyanıza aşağıdakileri ekleyin:

```cfg
gamemode0 mymod 1
plugins crashdetect sscanf streamer a_mysql
filterscripts gl_actions gl_property
```

## 🔐 Veritabanı Bağlantısı

- Host: `localhost`
- Kullanıcı: `root`
- Şifre: `""` (boş)
- Veritabanı: `safir`

## 📜 Lisans

MIT Lisansı ile yayınlanmıştır. Orijinal yazarların emeklerine saygı göstermek adına kodların referansla kullanılması rica olunur.
