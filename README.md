# Master Roleplay - Fine-Tuned Mod (Tanıtım) (2016)

Bu mod, 2016 yılında çeşitli SA:MP Roleplay altyapılarının harmanlanması ve zamanla birçok düzenleme (fine-tuning) yapılması ile oluşturulmuştur. PAWN diliyle yazılmıştır.

Bu proje, o dönemde kurduğum "Master RPG" sunucusunun temel modifikasyonlarını ve sistem mimarisini temsil eder. Kodların tamamı sıfırdan yazılmamış olsa da, **sistem geçişleri, yeniden yapılanmalar, performans ayarları ve özelleştirme işlemleri şahsıma aittir.**

---

## 🧠 Tarafımdan Yapılan Öne Çıkan Düzenlemeler

- 🎛 **Yüzlerce `#define`, `enum`, `MAX_` ve sabit** yeniden yapılandırıldı
- 🔧 **Karmaşık dialog ID’leri sadeleştirildi**, `DIALOG_` yapıları yeniden adlandırıldı
- 🚓 **MDC (polis bilgisayarı), admin yetkilendirme ve ceza sistemi** optimize edildi
- 🔊 **Boombox, radyo stream ve ses sistemi** entegre edildi (stream URL destekli)
- 🚪 **Gate/Kapı kontrol sistemi** detaylandırıldı (LSPD, FBI, mekan içi geçişler)
- 💼 **Meslekler** tek tek elden geçirildi (Dedektif, Pizza, Avukat, Tır, vb.)
- 💬 **Anti-flood, AFK, PM, spam koruması** güncellendi ve sadeleştirildi
- 🧪 **DEAKTIF tag sistemi** ile test sistemleri ayrıştırıldı
- 🧱 **Veritabanı mantığı** yeniden kuruldu (a_mysql uyumlu, UTF8 destekli)

---

## ✨ Genel Özellikler

- Kayıt / Giriş sistemi (MySQL destekli)
- Meslekler, iş sistemleri (Dedektif, Taksi, Pizza, Tır, vb.)
- Admin panel ve yetkilendirme sistemi
- Ev, araç, kilit, anahtar sistemleri
- Uyuşturucu, eskort, boks gibi detaylı yan sistemler
- Boombox, radyo stream, müzik sistemi
- MDC (polis bilgisayarı), cezalandırma ve oyuncu yönetimi
- Çok sayıda tanımlı renk, TextDraw, 3DText sistemi
- Anti-cheat ve flood koruma gibi temel güvenlik sistemleri

---

## ⚠️ Not

Bu mod tamamen sıfırdan yazılmamıştır. SA:MP RP modları temel alınmış, zaman içinde düzenlenmiş, optimize edilmiş ve yeniden yapılandırılmıştır. Bu repo yalnızca tanıtım ve arşiv amaçlıdır. **Master RPG sunucusunun temel altyapısını temsil eder.**

---

## 🛠 Kurulum

1. `gamemodes/mymod.pwn` dosyasını sunucu dizinine atın.
2. `include/`, `filterscripts/`, `plugins/` klasörlerini uygun içerikle doldurun.
3. `server.cfg` dosyanıza aşağıdakileri ekleyin:

```cfg
gamemode0 mymod 1
plugins crashdetect sscanf streamer a_mysql
filterscripts gl_actions gl_property
