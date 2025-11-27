# AesirMC-hile-koruma
# AesirMC AntiCheat

AesirMC için geliştirilmiş, Java tabanlı modern ve performans odaklı AntiCheat (hile koruma) sistemidir.  
Amacı; PvP sunucularında adil oyunu sağlamak ve yaygın hileleri minimum yanlış pozitif ile tespit etmektir.

> 📌 Durum: **BETA / Geliştirme Aşamasında**

---

## 🚫 Tespit Edilen Hile Türleri
- KillAura
- Speed
- Fly
- AutoClicker

---

## ⚙️ Kurulum
1. `.jar` uzantılı plugin dosyasını `plugins` klasörüne atın  
2. Sunucuyu yeniden başlatın  
3. Konsolda başarıyla yüklendi mesajını gördükten sonra sistem aktif olur

---

## 🧾 Komutlar
| Komut | Açıklama |
|------|----------|
| `/aesirreload` | AntiCheat sistemini yeniden yükler |
| `/aesiralerts` | Hile uyarılarını açar / kapatır |

---

## 🔐 Yetkiler (Permissions)
| Yetki | Açıklama |
|-------|----------|
| `aesir.admin` | Tüm yetkilere erişim |
| `aesir.alert` | Hile uyarılarını görme |
| `aesir.reload` | Sistemi yeniden yükleme |

---

## 📂 Config Sistemi
Tüm kontroller `config.yml` üzerinden açılıp kapatılabilir:

```yml
killaura:
  enabled: true

speed:
  enabled: true

fly:
  enabled: true

autoclicker:
  enabled: true

