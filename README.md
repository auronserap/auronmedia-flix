# AuronMedia - FlixMedia Benzeri İçerik Çözümü

Bu proje, ürün açıklamalarınızı Trendyol, Hepsiburada ve diğer e-ticaret pazaryerlerinde zengin içerikle göstermek için geliştirilmiş basit bir çözümdür. FlixMedia benzeri bir işlevsellik sunar ancak ücretsiz ve tamamen size özeldir.

## Nasıl Çalışır?

Bu çözüm, iframe teknolojisi kullanarak ürün içeriklerinizi pazaryerlerine entegre etmenizi sağlar. Her ürün için özel olarak hazırlanmış içerikler, basit bir iframe kodu ile pazaryerlerinin ürün açıklama alanlarına eklenebilir.

## Dosyalar

1. **urun-8681987831287.html**: Belirli bir ürün için statik HTML sayfası örneği
2. **urun-sayfasi.html**: Dinamik ürün gösterimi yapan JavaScript tabanlı sayfa
3. **iframe-ornegi.html**: Pazaryeri sayfasında iframe kullanım örneği

## Kullanım

### 1. Statik Kullanım
Her ürün için ayrı bir HTML dosyası oluşturarak kullanabilirsiniz:

```html
<iframe id="urun-container" src="https://sizin-sunucunuz.com/urun-8681987831287.html" style="height: 800px; min-width: 100%; border: none;"></iframe>
```

### 2. Dinamik Kullanım
Tek bir dosya ile tüm ürünlerinizi URL parametresi kullanarak gösterebilirsiniz:

```html
<iframe id="urun-container" src="https://sizin-sunucunuz.com/urun-sayfasi.html?id=8681987831287" style="height: 800px; min-width: 100%; border: none;"></iframe>
```

## Kurulum

1. Bu dosyaları bir web sunucusuna yükleyin (GitHub Pages, Netlify, Vercel veya herhangi bir hosting hizmeti)
2. Ürün içeriklerinizi uygun formatta hazırlayın
3. İframe kodunu pazaryeri ürün açıklamalarınıza ekleyin

## Otomatik Yükseklik Ayarlama

Sayfalara yerleştirilen JavaScript kodu, içeriğin yüksekliğini otomatik olarak hesaplayıp iframe'in yüksekliğini buna göre ayarlar. Bu sayede kaydırma çubuğu olmadan tüm içerik görüntülenir.

## İçerik Yönetimi

Büyük ölçekli kullanım için, içeriklerinizi bir veritabanında tutmanız ve dinamik olarak sunmanız önerilir. Bu sayede tek bir değişiklikle tüm pazaryerlerindeki içeriğinizi güncelleyebilirsiniz.

## Özelleştirme

HTML, CSS ve JavaScript kodlarını kendi ihtiyaçlarınıza göre özelleştirebilirsiniz. Mevcut kodlar, temel bir yapı sunmaktadır. Kendi marka kimliğinize ve ürün yapınıza göre düzenleyebilirsiniz.

## Nasıl Geliştirilebilir?

- JSON dosyaları ile ürün verilerini yönetebilirsiniz
- Basit bir CMS sistemi ekleyebilirsiniz
- İstatistik toplama özellikleri ekleyebilirsiniz
- Dil seçeneği ekleyebilirsiniz

## Lisans

Bu proje, kişisel ve ticari kullanım için tamamen ücretsizdir. 