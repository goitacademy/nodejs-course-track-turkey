## Ders Planı

Kahoot https://create.kahoot.it/details/3b150cb9-00eb-4121-a5da-06bf0a1d4531

1. Kullanıcı kaydı sürecini oluşturuyoruz

- Name, email, password alanlarına sahip yeni bir User koleksiyonu
- Kayıt için rota
- Şifreleme ve neden gerekli olduğu
- Modelde toJSON metodunu yeniden yazarak yanıttan şifrenin kaldırılması

2. Kullanıcı giriş sürecini oluşturuyoruz

- Gönderilen parolanın veritabanında kayıtlı olanla karşılaştırılması
- Oturum mekanizması, erişim+yenileme jetonları
- userId, accessToken, refreshToken, accessTokenValidUntil, refreshTokenValidUntil alanlarına sahip yeni bir Session koleksiyonu
- Giriş sırasında oturum oluşturma
- Çerezler, başlıkların ayrı bir türü olarak, çerezleri ayrıştırmak için cookie-parser kütüphanesi, yanıt içinde refreshToken'ı çerezlerde iletme

3. Çıkış yapmayı oluşturuyoruz

- Veritabanından oturumun silinmesi
- Oturumla ilgili çerezlerin silinmesi
