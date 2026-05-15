# 🧭 RotaBrowser (Özgün Tarayıcı Çekirdeği)

**RotaBrowser**, web tabanlı uygulamalarınızı (CRM, ERP, Otomasyon Panelleri, Saha Sistemleri) sanki yerel bir masaüstü (Desktop) programıymış gibi çalıştırmanızı sağlayan **özelleştirilebilir (White-Label)** bir web kiosk ve tarayıcı altyapısıdır.

## 💡 Neden RotaBrowser?

Geliştirdiğiniz web projelerini müşterilerinize sunarken standart bir Chrome veya Edge penceresi kullanmak kurumsal algıyı düşürebilir. RotaBrowser; dışarıdan gelen URL çubuğunu, gereksiz tarayıcı sekmelerini ve karmaşayı gizleyerek kullanıcıyı tamamen **sizin belirlediğiniz rotada** tutar. 

Müşterileriniz sadece tek bir `.exe` dosyasını çalıştırır ve doğrudan sizin uygulamanıza, sizin markanızla giriş yapar.

## 🚀 Temel Özellikler

* **Kurumsal Kimlik (White-Label):** Uygulama adı, görev çubuğu başlığı ve program ikonu klasördeki `appicon.ico` ve `appsettings.json` üzerinden anında değiştirilebilir. Kod derlemeye gerek kalmaz.
* **Tam Kiosk Modu (Monitörü Kapla):** F11 tuşu ile Windows görev çubuğunun (Taskbar) tamamen üzerine çıkarak cihazı tam bir dijital panoya (Digital Signage / Kiosk) çevirir.
* **İzole Veri Yapısı:** Belirlediğiniz "Uygulama Adı"na göre arka planda o projeye özel bir Windows LocalAppData klasörü oluşur. Aynı bilgisayarda birden fazla RotaBrowser çalışsa bile çerezler ve oturumlar asla birbirine karışmaz.
* **Tek Dosya (Single File Publish):** Karmaşık DLL dosyalarıyla uğraşmanıza gerek kalmaz. Uygulama sadece `RotaBrowser.exe`, ayar dosyası (`.json`) ve ikonunuzdan oluşur.
* **Gelişmiş Güvenlik & Şifreleme:** Uygulama içi ayar menüsü şifreyle korunur. Şifreler sisteminize özel olarak AES ile şifrelenir.
* **Modüler Arayüz:** Geri/İleri butonları, URL çubuğu, Sekme yapısı ve Otomatik Yenileme gibi tüm özellikler JSON dosyasından açılıp kapatılabilir.

## 🛠 Teknolojiler
* **Dil:** C#
* **Arayüz:** WPF (Windows Presentation Foundation) / WindowChrome
* **Web Motoru:** Microsoft Edge WebView2 (Chromium)
* **Framework:** .NET 8.0

## 📦 Kurulum ve Kullanım

1. Projeyi indirin ve Release klasörüne gidin.
2. `appicon.ico` dosyasını kendi şirket/proje logonuz ile değiştirin.
3. `appsettings.json` dosyasını metin editörü ile açarak `AppName` ve `TargetUrl` (başlangıç adresiniz) kısımlarını kendinize göre düzenleyin.
4. `RotaBrowser.exe` uygulamasını çalıştırın.

---
*Bu proje, kapalı devre web sistemlerini profesyonel bir masaüstü deneyimiyle sunmak isteyen geliştiriciler için tasarlanmıştır.*


<img width="1201" height="800" alt="Screenshot_6" src="https://github.com/user-attachments/assets/5d3f8637-dccb-461a-af55-955f90b0758d" />

<img width="589" height="1421" alt="22" src="https://github.com/user-attachments/assets/7057e712-a938-42be-9e10-6961fd6f7dd4" />
