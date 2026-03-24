# LiteSite

Lite-Site, sunucu ve veritabanı gerektirmeden çalışan; işletmelerin dijital menü oluşturup siparişlerini doğrudan müşterinin WhatsApp mesajıyla almasını sağlayan basit ve düşük maliyetli bir web çözümüdür.

---

## Ne Yaparsınız?

`settings/` klasöründeki dosyaları düzenleyip `bash update.sh` komutunu çalıştırırsınız. Komut tüm HTML sayfalarını, CSS/JS dosyalarını, site haritasını ve SEO için gerekli meta etiketleri, yapısal veri (schema) işaretlemelerini otomatik olarak oluşturur.

1. **İşletme bilgileri** — `settings/company.json` dosyasında adınız, adresiniz, telefonunuz, sosyal medya bağlantılarınız yer alır.

2. **Ürünler** — `settings/products/` klasöründe her ürün için bir dosya bulunur. İçinde ürün adı, fiyatı, açıklaması ve görseli tanımlıdır. Yeni ürün eklemek için mevcut bir dosyayı kopyalayıp içeriğini değiştirmeniz yeterlidir.

3. **Sayfalar** — `settings/pages/` klasöründe gizlilik politikası, satış sözleşmesi gibi sayfalar bulunur. Yeni sayfa eklemek için mevcut bir dosyayı kopyalayıp içeriğini düzenleyebilirsiniz.

---

## GitHub Codespaces ile Çalıştırma

Bilgisayarınıza hiçbir şey kurmanız gerekmez, her şeyi tarayıcıdan yaparsınız.

1. GitHub'da projenin sayfasında yeşil **Code** butonuna tıklayın.
2. **Codespaces** sekmesinden **Create codespace on main** butonuna tıklayın.
3. Açılan editörde sol panelden `settings/` klasörünü bulup dosyaları düzenleyin.
4. Alt taraftaki terminalde `bash update.sh` yazıp Enter'a basın.
5. Sol panelde **Source Control** simgesine (dal şeklindeki ikon) tıklayın. Değişen dosyaları göreceksiniz. Üstteki mesaj kutusuna `site guncellendi` yazıp **Commit** butonuna basın. Ardından **Sync Changes** butonuna tıklayarak değişiklikleri gönderin.

GitHub Pages aktifse siteniz kısa süre içinde güncellenir.
