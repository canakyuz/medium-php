# 2. Backend Geliştirme

## Genel Bakış
Bu aşamada, öğrenciler PHP kullanarak uygulamanın sunucu tarafı mantığını geliştirecekler. Veritabanı işlemleri, API endpoint'leri ve temel iş mantığı bu aşamada uygulanacak.

## Detaylı Adımlar

### 2.1 Veritabanı Bağlantısı ve ORM Kurulumu
- PDO veya MySQLi kullanarak veritabanı bağlantısı oluşturma
- Basit bir ORM sistemi kurma veya mevcut bir ORM kütüphanesi seçme (örn. Doctrine)
- Model sınıflarını oluşturma (User, Article, Comment, Tag)

### 2.2 Kullanıcı Kimlik Doğrulama Sistemi
- Kullanıcı kaydı işlevselliği
- Giriş ve çıkış işlevselliği
- Şifre hash'leme ve güvenli saklama
- Oturum yönetimi

### 2.3 CRUD İşlemleri
- Makaleler için CRUD (Create, Read, Update, Delete) işlemleri
- Yorumlar için CRUD işlemleri
- Kullanıcı profili yönetimi

### 2.4 Routing Sistemi
- URL'leri controller ve action'lara eşleyen bir routing sistemi oluşturma
- RESTful API prensiplerini uygulama

### 2.5 Controller'ların Geliştirilmesi
- UserController: Kullanıcı işlemleri için
- ArticleController: Makale işlemleri için
- CommentController: Yorum işlemleri için

### 2.6 Temel İş Mantığı
- Makale oluşturma ve düzenleme kuralları
- Yorum moderasyon sistemi
- Kullanıcı yetkilendirme kontrolleri

## Önemli Kavramlar
- ORM (Object-Relational Mapping)
- RESTful API tasarımı
- Kimlik doğrulama ve yetkilendirme
- CRUD işlemleri
- MVC yapısında Controller'ların rolü

## Öğretmen İçin İpuçları
- ORM kavramını ve faydalarını detaylı olarak açıklayın
- Güvenli şifre saklama yöntemlerini vurgulayın (bcrypt, Argon2 gibi)
- RESTful API tasarımı üzerine bir workshop düzenleyin
- Öğrencilere gerçek dünya senaryoları sunarak CRUD işlemlerini uygulamalarını sağlayın
- Kod tekrarını önleme ve DRY (Don't Repeat Yourself) prensibini vurgulayın

## Kaynaklar
- [PHP PDO Dokümantasyonu](https://www.php.net/manual/en/book.pdo.php)
- [Doctrine ORM Dokümantasyonu](https://www.doctrine-project.org/projects/orm.html)
- [PHP Password Hashing](https://www.php.net/manual/en/faq.passwords.php)
- [RESTful API Tasarım Rehberi](https://restfulapi.net/)

Bu aşamayı tamamladıktan sonra, öğrenciler uygulamanın temel backend yapısını oluşturmuş olacaklar. Bir sonraki aşamada frontend geliştirmeye geçebilirsiniz.

