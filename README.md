# Telegram to Google Sheets Automation with n8n 🚀

Bu proje, **n8n** otomasyon aracı kullanılarak geliştirilmiştir. Telegram botuna gönderilen mesajları otomatik olarak yakalar, tarih ve kullanıcı bilgisiyle birlikte **Google Sheets** (E-Tablo) dosyasına kaydeder ve kullanıcıya işlemin başarılı olduğuna dair geri bildirim gönderir.

<img width="1441" height="705" alt="Ekran görüntüsü 2025-11-27 004400" src="https://github.com/user-attachments/assets/9df90428-ef6c-4cd3-9785-1dda1b885660" />

<img width="1902" height="632" alt="Ekran görüntüsü 2025-11-27 005011" src="https://github.com/user-attachments/assets/a2c48754-9b36-4bb7-b8de-e4b8a19fa23a" />

![WhatsApp Image 2025-11-27 at 01 24 56](https://github.com/user-attachments/assets/9dd5c49e-ff4c-4614-85a4-472f455570ed)


## 🛠️ Kullanılan Teknolojiler
- **n8n** (Workflow Automation)
- **Telegram Bot API**
- **Google Sheets API**
- **Google Cloud Console** (OAuth2 Kimlik Doğrulaması)

## 📋 Nasıl Çalışır?
1. **Telegram Trigger:** Kullanıcı Telegram botuna bir mesaj gönderir.
2. **Google Sheets Action:** n8n bu mesajı alır; gönderen kişinin adını, mesaj içeriğini ve tarih/saat bilgisini Google E-Tablo'ya yeni bir satır olarak ekler.
3. **Telegram Response:** İşlem başarılı olduğunda bot, kullanıcıya "Kaydedildi" mesajı döner.
