# Proxy türleri: ağ, atama ve protokol

Bu rehberi, görev, oturum, konum ve maliyete göre sağlayıcıları karşılaştıran bir dizin olan [ProxyVendors](https://proxyvendors.com/tr/) sitesini de işleten Northleaf Studio yayımlar. Aynı tarafın arka plan metnidir; o sitenin ya da bir sağlayıcının ilgisiz bir üçüncü tarafça yapılmış bağımsız incelemesi değildir. Ürün etiketleri değişir ve aynı sağlayıcının iki resmî sayfası ayrışabilir. Bunu terimlerin haritası olarak kullanın, ayrıntıları sağlayıcının güncel belgesinde doğrulayın.

## Diller

- [English](../../guides/proxy-types.md)
- [简体中文](../../zh-cn/guides/proxy-types.md)
- [Español](../../es/guides/proxy-types.md)
- [Deutsch](../../de/guides/proxy-types.md)
- [Français](../../fr/guides/proxy-types.md)
- [日本語](../../ja/guides/proxy-types.md)
- [Português](../../pt/guides/proxy-types.md)
- [한국어](../../ko/guides/proxy-types.md)
- [اردو](../../ur/guides/proxy-types.md)
- [Bahasa Indonesia](../../id/guides/proxy-types.md)
- **Türkçe**
- [العربية](../../ar/guides/proxy-types.md)
- [Polski](../../pl/guides/proxy-types.md)
- [Italiano](../../it/guides/proxy-types.md)
- [ไทย](../../th/guides/proxy-types.md)
- [Українська](../../uk/guides/proxy-types.md)
- [Tiếng Việt](../../vi/guides/proxy-types.md)
- [Русский](../../ru/guides/proxy-types.md)

## Üç ayrı soru

İnsanlar çoğu zaman üç soruyu tek bir sözcüğe, “proxy”ye sıkıştırır:

1. **Çıkış IP’si ne tür bir ağdan gelir?** Konut, veri merkezi, ISP ve mobilin alışılmış anlamı budur.
2. **Aynı çıkış ne kadar süre atanmış kalır?** Bu, sabit ile dönen arasındaki ayrımdır; bazen yapışkan oturum denir.
3. **İstemci nasıl bağlanır?** Bu HTTP’dir; HTTPS için kullanılan [HTTP CONNECT](https://proxyvendors.com/tr/glossary/http-connect) tünelini ya da [SOCKS5](https://proxyvendors.com/tr/glossary/socks5) protokolünü kapsar.

Sabit bir IP yine de başka müşterilerle paylaşılabilir. Bir SOCKS5 uç noktası bir bağlantı yöntemidir, bir IP türü değildir. Aynı konut ya da veri merkezi çıkışına çoğu zaman birden fazla protokolle ulaşılır; bazı ürünler yalnızca HTTP ya da HTTPS destekler.

## Ağ türleri

**Konut.** Çıkış, bir tüketici ya da geniş bant ağıyla ilişkilidir. Hedef barındırma aralıklarına duyarlıysa ya da sıradan bir ev bağlantısı gibi görünen bir konum gerekiyorsa alışılmış seçim budur. Konut trafiği çoğu zaman gigabayt başına ücretlendirilir. Havuzlar paylaşılır ve yapışkan ya da ayrılmış bir seçenek alınmadıkça döner. Etiket, sağlayıcının ya da üçüncü taraf veritabanlarının sınıflandırmasıdır; IP’nin kendisinin taşıdığı bir alan değildir.

**Veri merkezi.** Çıkış bir barındırma ya da bulut ağından gelir. Bu ürünler trafik birimi ya da IP başına daha ucuz olabilir ve büyük istek hacimlerinde daha yüksek aktarım sunabilir. Birçok site veri merkezi aralıklarını daha sıkı ele alır. Büyük bir plan almadan önce hedefin bu tür bir çıkış üzerinden geçerli içerik döndürüp döndürmediğini kontrol edin.

**ISP; bazen sabit konut olarak satılır.** Adres tipik olarak bir konut internet erişim sağlayıcısına kayıtlıdır, proxy sunucusunun kendisi ise çoğu zaman bir veri merkezindedir. ISP bu kaydı adlandırır; tek başına çıkışın sabit kaldığı anlamına gelmez. Satıcılar etiketi çoğu zaman daha uzun bir atamayla birlikte sunar. Bu, oturum açma, IP izin listeleri ve sabit bir konum için yaygın bir eşleşmedir. IP’nin size ayrılmış mı yoksa paylaşımlı mı olduğunu, bağlantı kopunca ya da yenilemede ne olduğunu ve kimlik kontrolü gerekip gerekmediğini doğrulayın.

**Mobil.** Çıkış bir mobil operatör ağından, genellikle 4G ya da 5G’den gelir. Mobil reklamlar, operatöre özgü sayfalar ve hücresel ağlarda değişen bölgesel içerik için kullanılır. Ücretlendirme gigabayt, gün ya da port başına olabilir. Operatör ve ülke stoğunu, dönüş kurallarını ve kullanım sınırlarını kontrol edin; mobil envanter konut havuzlarından daha ince olur.

Bu etiketlerin hiçbiri bir kalite puanı değildir. Hedefin isteği kabul edip etmemesi çıkışa, istek düzenine ve hedefin kendi politikasına bağlıdır.

## Atama: sabit, dönen ve yapışkan

Dönen, genellikle her istekte ya da kısa aralıklarla yeni bir çıkış seçilmesi demektir. Yapışkan ya da sabit, genellikle aynı çıkışın bir oturum ya da kiralama süresi boyunca tutulması demektir. Sağlayıcılar bu sözcükleri aynı şekilde kullanmaz ve resmî sayfalar bazen iki farklı oturum süresi verir. Göreviniz aynı IP’yi gerektiriyorsa kesin tutma süresini, bunu bozan koşulları ve yedek bir IP’nin güvence altına alınıp alınmadığını öğrenin.

## ASN dördüncü bir tür değildir

Bir [ASN](https://proxyvendors.com/tr/glossary/asn), bir adres bloğunu duyuran yönlendirme işletmecisini belirtir. Tek bir operatörün ağı gerektiğinde bir ülkeden daha kesin olabilir. Bir ülke değildir ve IP’nin konut mu yoksa veri merkezi mi olduğunu söylemez. Tek bir ASN istemek havuzu da küçültür; uygun çıkış yoksa istek başarısız olabilir.

## Türü seçtikten sonra çıkışı kontrol edin

Plan sayfaları, almayı amaçladığınız ürünü anlatır. [IP kontrolü](https://proxyvendors.com/tr/ip-check) gerçekten aldığınız genel IP’yi, kuruluşu ve ASN’yi gösterir; DNS ve WebRTC kontrolleri isteğe bağlıdır. Sonuçlar satın alınan ürünle uyuşmuyorsa ölçeği büyütmeden önce durup bunu giderin.

Belirli bir planı karşılaştırırken [satın alma listesini](./buying-checklist.md) kullanın.

— Northleaf Studio
