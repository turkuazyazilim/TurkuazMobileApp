# Gizlilik Politikası

**Son Güncelleme:** 23 Ocak 2026

Turkuaz Mobil uygulamasını kullandığınız için teşekkür ederiz. Bu gizlilik politikası, uygulamamızın kişisel verilerinizi nasıl topladığını, kullandığını ve koruduğunu açıklamaktadır.

## Toplanan Veriler

### Cihaz İzinleri
Uygulamamız aşağıdaki cihaz izinlerini kullanmaktadır:

- **Kamera:** Barkod okuma işlemleri için kullanılır.
- **Depolama:** Uygulama verilerini cihazınızda saklamak için kullanılır.
- **İnternet:** Sunucu ile veri senkronizasyonu için kullanılır.
- **Ağ Durumu:** İnternet bağlantı durumunu kontrol etmek için kullanılır.

### Cihaz Bilgileri
Uygulama, aşağıdaki cihaz bilgilerini toplar ve işler:

- **Cihaz Kimliği (Device ID):** Cihazınızı benzersiz şekilde tanımlamak için kullanılır.
- **Cihaz Model Adı:** Cihaz yönetimi ve tanımlama için kullanılır.
- **Uygulama Sürümü:** Uyumluluk ve güncelleme kontrolü için kullanılır.

### Yerel Veri Depolama
Uygulama, çalışması için gerekli verileri cihazınızın yerel depolama alanında SQLite veritabanı kullanarak saklar. **Bu veriler yalnızca cihazınızda tutulur ve harici sunuculara gönderilmez.**

## Veri Saklama Süresi

- **Yerel Veriler:** Uygulama verileri, siz uygulamayı silene veya "Hard Reset" özelliğini kullanana kadar cihazınızda saklanır.
- **Sunucu Verileri:** Uygulama, kullanıcı verilerini kalıcı olarak harici sunucularda saklamaz. Sunucu ile yapılan iletişimler yalnızca anlık veri senkronizasyonu içindir.
- **Hata Günlükleri:** Hata günlükleri cihazda geçici olarak saklanır ve kullanıcı tarafından manuel olarak silinebilir.

## Kurumsal Kullanım (B2B)

Bu uygulama, **işletmeden işletmeye (B2B)** kurumsal kullanım için tasarlanmıştır. Bireysel tüketicilere yönelik değildir. Uygulama, şirketinizin depo, stok ve sevkiyat yönetimi operasyonlarını desteklemek amacıyla kullanılmaktadır.

## Uzaktan Yönetim ve Yapılandırma

Uygulamamız, kurumsal kullanım için **uzaktan yönetim** özelliklerine sahiptir. Bu özellikler:

### Gerçek Zamanlı Bağlantı
- Uygulama, merkezi yönetim paneli ile gerçek zamanlı bağlantı kurabilir (SignalR teknolojisi kullanılarak).
- Bağlantı durumu (çevrimiçi/çevrimdışı) merkezi panel tarafından izlenebilir.
- Bağlantı sırasında cihaz kimliği, cihaz adı ve uygulama sürümü iletilir.

### Uzaktan Yapılandırma
Yetkili sistem yöneticileri, merkezi panel üzerinden aşağıdaki işlemleri gerçekleştirebilir:

- Uygulama ayarlarını uzaktan görüntüleme ve değiştirme
- Bildirim gönderme
- Veri senkronizasyonu tetikleme (ürün, stok verileri vb.)
- Hata günlüklerini görüntüleme (sorun giderme amacıyla)
- Oturum sonlandırma (güvenlik amaçlı zorla çıkış)

### Veri Sorgulama (Teknik Destek)
Teknik destek ve sorun giderme amacıyla, yetkili yöneticiler cihazınızdaki yerel veritabanına **salt okunur** sorgular gönderebilir. Bu özellik:

- Yalnızca **şirketinizin kendi yönetim paneli** üzerinden erişilebilir
- Turkuaz Yazılım bu verilere **erişemez** - kontrol tamamen şirketinize aittir
- Sadece uygulama içi verileri (ürünler, stok, ayarlar vb.) sorgular
- Kişisel dosyalarınıza veya diğer uygulamalara erişemez
- Tüm sorgular kayıt altına alınır ve denetlenebilir
- Veri değiştirme veya silme işlemi **yapamaz**

### Önemli Notlar
- Uzaktan yönetim özellikleri yalnızca **şirketinizin kendi sunucusuna kurulu yönetim paneli** üzerinden kullanılabilir.
- Turkuaz Yazılım, cihaz verilerinize doğrudan erişim sağlamaz; tüm kontrol şirketinizin IT yöneticilerine aittir.
- Bu özellikler, uygulama kodunu değiştirmez; yalnızca mevcut yapılandırma değerlerini günceller.
- Tüm uzaktan işlemler, güvenli ve şifreli bağlantılar (WSS/HTTPS) üzerinden gerçekleştirilir.

## Hata Günlükleri

Uygulama, teknik sorunların çözümü için anonim hata günlükleri toplayabilir. Bu günlükler:

- Hata mesajları ve stack trace bilgileri
- Hatanın oluştuğu modül bilgisi
- Cihaz ve uygulama sürüm bilgisi

içerebilir. Bu veriler kişisel bilgi içermez ve yalnızca teknik sorun giderme amacıyla kullanılır.

## Üçüncü Taraf Hizmetler

Bu uygulama, üçüncü taraf analitik veya reklam hizmetleri **kullanmamaktadır**. Verileriniz üçüncü taraf şirketlerle paylaşılmaz.

## Veri Kullanımı

Toplanan veriler aşağıdaki amaçlarla kullanılır:

- Uygulama işlevselliğini sağlamak
- Kullanıcı deneyimini iyileştirmek
- Sunucu ile veri senkronizasyonu yapmak
- Kurumsal cihaz yönetimi ve izleme
- Teknik sorunları tespit etmek ve çözmek

## Veri Paylaşımı

Kişisel verileriniz üçüncü taraflarla paylaşılmaz, satılmaz veya kiralanmaz. Verileriniz yalnızca:

- Yasal zorunluluklar gerektirdiğinde
- Hizmet sağlayıcınızın (şirketinizin) sunucuları ile senkronizasyon amacıyla
- Kurumsal yönetim paneli ile yapılandırma senkronizasyonu amacıyla

paylaşılabilir.

## Kullanıcı Hakları

KVKK (Kişisel Verilerin Korunması Kanunu) ve GDPR kapsamında aşağıdaki haklara sahipsiniz:

- **Erişim Hakkı:** Hangi verilerinizin toplandığını öğrenme
- **Düzeltme Hakkı:** Yanlış veya eksik verilerin düzeltilmesini isteme
- **Silme Hakkı:** Verilerinizin silinmesini talep etme
- **Veri Taşınabilirliği:** Verilerinizin size verilmesini isteme
- **İtiraz Hakkı:** Veri işlenmesine itiraz etme

### Verilerinizi Silme

Cihazınızdaki tüm uygulama verilerini silmek için:
1. Uygulama içinde **Ayarlar > Hard Reset** seçeneğini kullanın
2. Veya uygulamayı cihazınızdan tamamen kaldırın

Bu haklarınızı kullanmak için aşağıdaki iletişim bilgilerinden bize ulaşabilirsiniz.

## Veri Güvenliği

Verilerinizin güvenliğini sağlamak için endüstri standardı güvenlik önlemleri uygulanmaktadır:

- Tüm veri iletişimleri HTTPS/WSS protokolleri ile şifrelenir
- Kimlik doğrulama token tabanlı güvenlik sistemi ile sağlanır
- Yerel veriler cihazınızda güvenli şekilde saklanır

Ancak, internet üzerinden yapılan hiçbir veri iletiminin %100 güvenli olmadığını hatırlatmak isteriz.

## Çocukların Gizliliği

Bu uygulama 13 yaşın altındaki çocuklara yönelik değildir ve bilerek çocuklardan kişisel veri toplamaz.

## Değişiklikler

Bu gizlilik politikası zaman zaman güncellenebilir. Önemli değişiklikler olduğunda uygulama içi bildirim ile kullanıcılar bilgilendirilecektir. Değişiklikler bu sayfada yayınlanacaktır.

## İletişim

Gizlilik politikamız veya haklarınız hakkında sorularınız için bizimle iletişime geçebilirsiniz:

- **E-posta:** info@turkuazyazilim.com.tr
- **Şirket:** Turkuaz Yazılım

---

# Privacy Policy

**Last Updated:** January 23, 2026

Thank you for using Turkuaz Mobile application. This privacy policy explains how our application collects, uses, and protects your personal data.

## Data Collection

### Device Permissions
Our application uses the following device permissions:

- **Camera:** Used for barcode scanning operations.
- **Storage:** Used to store application data on your device.
- **Internet:** Used for data synchronization with the server.
- **Network State:** Used to check internet connection status.

### Device Information
The application collects and processes the following device information:

- **Device ID:** Used to uniquely identify your device.
- **Device Model Name:** Used for device management and identification.
- **Application Version:** Used for compatibility and update verification.

### Local Data Storage
The application stores necessary data in a local SQLite database on your device. **This data is kept only on your device and is not sent to external servers.**

## Data Retention Period

- **Local Data:** Application data is stored on your device until you uninstall the app or use the "Hard Reset" feature.
- **Server Data:** The application does not permanently store user data on external servers. Communications with the server are only for instant data synchronization.
- **Error Logs:** Error logs are temporarily stored on the device and can be manually deleted by the user.

## Enterprise Use (B2B)

This application is designed for **business-to-business (B2B)** enterprise use. It is not intended for individual consumers. The application is used to support your company's warehouse, inventory, and shipment management operations.

## Remote Management and Configuration

Our application includes **remote management** features for enterprise use. These features include:

### Real-Time Connection
- The application can establish real-time connection with the central management panel (using SignalR technology).
- Connection status (online/offline) can be monitored by the central panel.
- Device ID, device name, and application version are transmitted during connection.

### Remote Configuration
Authorized system administrators can perform the following operations through the central panel:

- View and modify application settings remotely
- Send notifications
- Trigger data synchronization (products, inventory data, etc.)
- View error logs (for troubleshooting purposes)
- Session termination (force logout for security purposes)

### Data Querying (Technical Support)
For technical support and troubleshooting purposes, authorized administrators can send **read-only** queries to the local database on your device. This feature:

- Can only be accessed through **your company's own management panel**
- Turkuaz Yazılım **cannot access** this data - control belongs entirely to your company
- Only queries in-app data (products, inventory, settings, etc.)
- Cannot access your personal files or other applications
- All queries are logged and auditable
- **Cannot** modify or delete data

### Important Notes
- Remote management features can only be used through **a management panel installed on your company's own server**.
- Turkuaz Yazılım does not have direct access to your device data; all control belongs to your company's IT administrators.
- These features do not modify application code; they only update existing configuration values.
- All remote operations are performed over secure, encrypted connections (WSS/HTTPS).

## Error Logs

The application may collect anonymous error logs for technical troubleshooting. These logs may include:

- Error messages and stack trace information
- Module information where the error occurred
- Device and application version information

This data does not contain personal information and is used solely for technical troubleshooting purposes.

## Third-Party Services

This application **does not use** third-party analytics or advertising services. Your data is not shared with third-party companies.

## Data Usage

Collected data is used for the following purposes:

- Providing application functionality
- Improving user experience
- Synchronizing data with the server
- Enterprise device management and monitoring
- Detecting and resolving technical issues

## Data Sharing

Your personal data is not shared, sold, or rented to third parties. Your data may only be shared:

- When required by legal obligations
- For synchronization purposes with your service provider's (company's) servers
- For configuration synchronization with the enterprise management panel

## User Rights

Under GDPR and applicable data protection laws, you have the following rights:

- **Right of Access:** Learn what data is collected about you
- **Right to Rectification:** Request correction of inaccurate or incomplete data
- **Right to Erasure:** Request deletion of your data
- **Right to Data Portability:** Request your data to be provided to you
- **Right to Object:** Object to data processing

### Deleting Your Data

To delete all application data on your device:
1. Use **Settings > Hard Reset** option within the app
2. Or completely uninstall the application from your device

To exercise these rights, please contact us using the contact information below.

## Data Security

Industry-standard security measures are implemented to protect your data:

- All data communications are encrypted using HTTPS/WSS protocols
- Authentication is provided through a token-based security system
- Local data is securely stored on your device

However, please note that no data transmission over the internet is 100% secure.

## Children's Privacy

This application is not intended for children under 13 years of age and does not knowingly collect personal data from children.

## Changes

This privacy policy may be updated from time to time. Users will be notified via in-app notification when significant changes occur. Changes will be published on this page.

## Contact

For questions about our privacy policy or your rights, please contact us:

- **Email:** info@turkuazyazilim.com.tr
- **Company:** Turkuaz Yazılım
