# PHP MYSQL Basit Üyelik Sistemi
PHP ve MYSQL kullanılarak yazılmış basit bir üyelik sistemi. Projeye eklenen yeni özellikler:

- Kullanıcılar kayıt olduğunda mailini doğrulaması gerekir.
- Şifre sıfırlama sayfası.

-----------------------------------------

### Dokümantasyon
- [Veritabanı Kurulum](#veritabanı-kurulum)
- [Mail Ayarları](#mail-ayarları)
- [Ekran Görüntüleri](#ekran-görüntüleri)
- [Demo Sayfası](#demo-sayfası)

-----------------------------------------

### Veritabanı Kurulum
Veritabanı oluşturun. `utf8_general_ci` seçili olmasına dikkat edin.

<img src="https://img001.prntscr.com/file/img001/ExkEhbzqTzKxXC0kOR1USA.png" width="100%" center />

`db` klasörü içerisindeki `db.sql` dosyasını phpMyAdmin'de oluşturduğunuz veritabanı içerisine `import` edin.

<img src="https://img001.prntscr.com/file/img001/0_8nuCeIQEmQ-gybVd9HkA.png" width="100%" center />

<img src="https://img001.prntscr.com/file/img001/sCCdaOyaTfC3GNKEQ4SMtQ.png" width="100%" center />

Son olarak `database.php` dosyasındaki alanları oluşturduğunuz veritabanına göre değiştirin.

-----------------------------------------

### Mail Ayarları
Kullanıcılar kayıt olabilmesi için hesaplarını doğrulaması gerekmektedir. Kullanıcının mailine doğrulama linkini gönderebilmek için `mail-config.php` dosyasındaki alanları kendi SMTP sunucunuza göre değiştirin.

Doğrulama mail örneği:

<img src="https://img001.prntscr.com/file/img001/E7CMnDLtRbWNRL7qPERGCQ.png" width="100%" center />

-----------------------------------------

### Ekran Görüntüleri
<img src="https://img001.prntscr.com/file/img001/IKQ_z71CQWq-TQObMVhRzg.png" width="100%" center />

<img src="https://img001.prntscr.com/file/img001/xOSDWcYDTeiekTxhrkab-Q.png" width="100%" center />

<img src="https://img001.prntscr.com/file/img001/9JhhIvn-SWy5AJPDnNU4pw.png" width="100%" center />

<img src="https://img001.prntscr.com/file/img001/RFBsQstKQzyDhtSDhGGvHw.png" width="100%" center />

<img src="https://img001.prntscr.com/file/img001/OzqfY7IQS5yqfyPrIPgFHw.png" width="100%" center />

