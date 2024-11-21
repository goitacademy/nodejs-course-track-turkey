## Ders Planı

Kahoot https://create.kahoot.it/details/214b58ac-c2f2-49a5-b31e-d39caff5b04f

1. Öğrencilere SMTP, POP3 protokolleri hakkında kısaca bilgi verin, mesaj göndermek için neden bir SMTP sunucusu kullanılması gerektiğini açıklayın.
2. E-posta yoluyla parola sıfırlama sürecinin genel akışını anlatın.
3. Body kısmında verilen e-posta adresine bir e-posta gönderilecek olan /auth/request-reset-password-email endpoint'ini oluşturun:

- Brevo'nun SMTP sunucusunu kullanarak mesaj göndermek için nodemailer kurulumunu anlatın.
- E-posta göndermek için gerekli minimum parametreler hakkında bilgi verin: html, to, from, subject.
- JWT, token payload'unun varsayılan alanları, jsonwebtoken kütüphanesi ile token oluşturma, jwt.io ile token hata ayıklama, güvenlik ile ilgili nüanslar (okunabilir, bilgi sahteciliği yapılamaz) hakkında bilgi verin.
- Handlebars şablonlayıcı kullanarak e-posta için HTML içeriği oluşturma ve şablonlama hakkında bilgi verin.

4. /auth/reset-password endpoint'ini oluşturun, frontend'den gelen JWT tokenine dayalı parola sıfırlama mantığını oluşturun.

- Token doğrulamasını unutmayın.
