## Ders Planı

Kahoot https://create.kahoot.it/details/c06d87ce-c070-44c8-869b-faef29dec82d

1. Çerezlerdeki yenileme tokenine dayalı olarak oturum yenileme işlevselliği oluşturun

- Oturumun ve onunla ilişkili kullanıcının varlığını kontrol edin (var olup olmadıklarını)
- refreshTokenValidUntil'e dayanarak tokenin geçerliliğini kontrol edin (hala geçerli mi)
- Oturumu yeniden oluşturun, access yenileme tokenini ve yanıt gövdesinde access tokenini istemciye geri gönderin

2. Rotalarda kullanıcı kimlik doğrulaması için bir middleware oluşturun:

- Authorization başlığı ve Bearer token hakkında bilgi verin
- authenticate ara yazılımında, Authorization başlığından tokeni alın. Başlığın, Bearer kelimesinin veya tokenin yokluğunda 401 hatası verin
- Oturumun ve onunla ilişkili kullanıcının varlığını kontrol edin (var olup olmadıklarını)
- accessTokenValidUntil'e dayanarak tokenin geçerliliğini kontrol edin (hala geçerli mi)
- Kullanıcıyı istek nesnesine ekleyin

3. Kontrolörlerde istek nesnesinden kullanıcı bilgilerini nasıl alabileceğinizi ve hizmetlerde daha doğru bir şekilde çalışmak için nasıl kullanabileceğinizi gösterin (öğrenci isteği oluştururken userId alanı ekleyin, yalnızca kendi kayıtlarıyla etkileşimde bulunma imkanı verin)
4. Kullanıcı modeline parent, teacher rolleri ekleyin. Bunlar üzerinden, rollerin varlığını kontrol eden ve şu imkanları veren bir middleware oluşturun:

- öğretmenin herhangi bir kısıtlama olmaksızın her türlü işlemi yapabilmesi
- ebeveynlerin yalnızca kendi çocukları için işlemler yapabilmesi
