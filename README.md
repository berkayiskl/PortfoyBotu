# 📁 Proje Yöneticisi Discord Botu

Bu Discord botu, kullanıcıların projelerini kolayca yönetmelerine olanak tanır. Kullanıcılar proje ekleyebilir, güncelleyebilir, beceri ekleyebilir, projeleri listeleyebilir veya silebilir. 
Bot, kullanıcılarla etkileşim kurarak bilgileri alır ve SQLite veritabanında saklar.

---

## 🔧 Özellikler

- ✅ Yeni proje ekleme (`!new_project`)
- 📋 Tüm projeleri listeleme (`!projects`)
- 🛠️ Projeye beceri ekleme (`!skills`)
- ✏️ Proje bilgilerini güncelleme (`!update_projects`)
- 🗑️ Proje silme (`!delete`)
- ℹ️ Komutları listeleme (`!info`)
- 👋 Karşılama mesajı (`!start`)

---

## 💬 Kullanılabilir Komutlar

| Komut | Açıklama |
|-------|----------|
| `!start` | Botu başlatır ve karşılama mesajı gönderir |
| `!info` | Kullanılabilir komutları listeler |
| `!new_project` | Yeni bir proje eklemenizi sağlar |
| `!projects` | Kayıtlı projelerinizi listeler |
| `!skills` | Seçilen bir projeye beceri ekler |
| `!update_projects` | Bir projeye ait bilgileri günceller |
| `!delete` | Seçilen bir projeyi siler |

---

## 📂 Dosya Yapısı

- `bot.py` – Discord botunun ana dosyası
- `logic.py` – Veritabanı yönetimi ve sorgular
- `config.py` – Bot token'ı ve veritabanı ayarı

---

## 🛠 Gereksinimler

- Python 3.8 veya üzeri
- `discord.py` kütüphanesi
- `sqlite3` (Python ile birlikte gelir)

```bash
pip install discord.py
