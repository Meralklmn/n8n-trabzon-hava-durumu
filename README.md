# n8n-trabzon-hava-durumu
Bu proje, Trabzon’daki güncel hava durumunu Open-Meteo API üzerinden çekip n8n üzerinde manuel olarak tetiklendiğinde e-posta ile bildirim göndermeyi amaçlayan bir iş akışıdır.
-Özellikler

API anahtarı gerektirmez
Trabzon’un anlık hava durumu verileri
Manuel tetikleme ile anında mail gönderimi
HTML formatlı rapor

-Kullanılan Teknolojiler

n8n (otomasyon platformu)
Open-Meteo API
SMTP E-mail Node

-Çalışma Adımları

Manual Trigger ile workflow başlatılır
HTTP Request ile hava durumu verisi alınır
E-mail bilgilerin mail olarak gönderimi sağlanır
