# Bir proxy planı almadan önce kısa bir liste

Bu listeyi, [ProxyVendors](https://proxyvendors.com/tr/) sitesini de işleten Northleaf Studio yayımlar. Aynı tarafın tamamlayıcı malzemesidir; ilgisiz bir üçüncü tarafın önerisi değildir. Sağlayıcının güncel fiyat sayfasına, koşullarına ve küçük bir denemeye karşı kullanın. Bir planın hedefinize uyacağını garanti etmez.

## Diller

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- [日本語](../../ja/guides/buying-checklist.md)
- [Português](../../pt/guides/buying-checklist.md)
- [한국어](../../ko/guides/buying-checklist.md)
- [اردو](../../ur/guides/buying-checklist.md)
- [Bahasa Indonesia](../../id/guides/buying-checklist.md)
- **Türkçe**
- [العربية](../../ar/guides/buying-checklist.md)
- [Polski](../../pl/guides/buying-checklist.md)
- [Italiano](../../it/guides/buying-checklist.md)
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- [Tiếng Việt](../../vi/guides/buying-checklist.md)
- [Русский](../../ru/guides/buying-checklist.md)

## 1. Görevi yazın, sonra ağı seçin

Çıkışın ne yapması gerektiğini yazın: uzun süreli bir oturum açma, belirli bir yere ait kamuya açık veri, yüksek hacimli istekler ya da bir mobil operatör denemesi. Bunu, [proxy türleri rehberinde](./proxy-types.md) anlatıldığı gibi bir ağ türüyle eşleştirin: konut, veri merkezi, ISP ya da mobil. Sağlayıcının ana sayfası ile fiyat sayfası farklı başlangıç fiyatları ya da ülke sayıları duyuruyorsa ikisini de kaydedin ve alacağınız kesin kademeye hangisinin uyduğunu sorun.

## 2. Oturum davranışını kontrol edin

Aynı çıkışa dakikalar, saatler ya da tüm kiralama boyunca mı ihtiyacınız olduğunu, yoksa her istekte yeni bir çıkış mı istediğinizi kararlaştırın. Yapışkan ya da sabit süreyi, bunu neyin bozduğunu ve düşen bir IP’nin değiştirilip değiştirilmediğini doğrulayın. Resmî belgeler bazen iki farklı tutma süresi verir; sağlayıcı doğrulayana kadar bunu çözülmemiş sayın.

## 3. Protokolleri ve kimlik doğrulamayı doğrulayın

HTTPS siteleri için [HTTP CONNECT](https://proxyvendors.com/tr/glossary/http-connect) dahil HTTP, [SOCKS5](https://proxyvendors.com/tr/glossary/socks5) ile aynı şey değildir. Bazı konut ürünleri yalnızca HTTP ve HTTPS destekler. SOCKS5 ya da SOCKS5 üzerinden UDP gerekiyorsa hem ürünün hem istemcinizin bunu desteklediğini kontrol edin. Giriş ana bilgisayarını, portu ve doğrulama yöntemini doğrulayın: kullanıcı adı ve parola, bir IP izin listesi ya da ikisi. CONNECT sırasında gelen 407 yanıtı proxy’den gelir. Durum, Proxy Authentication Required anlamına gelir: proxy kimlik doğrulama ister ya da aldığı doğrulamayı kabul etmemiştir. Tünel kurulmamıştır ve hedef site isteği hiç görmemiştir.

## 4. Gerçek maliyeti toplayın

Manşetteki birim fiyatın ötesine bakın. Asgari alımı, paketin geçerliliğini ya da son kullanma tarihini, aşım ücretlerini, yeniden denemelerden doğan israfı, ince hedefleme ek ücretlerini, KDV’yi ve otomatik yükleme ya da yenilemeleri not edin. Öne çıkarılan bir fiyat, başlayacağınız pakete değil, büyük bir hacim kademesine ait olabilir. Deneme kart istiyor ve otomatik yüklemeyi açıyorsa, deneme başlamadan önce bunu kapatıp kapatmayacağınıza karar verin.

## 5. Deneme, iade ve erişim kurallarını okuyun

Denemenin boyutunu ve süresini, iade penceresini, kullanım tavanlarını ve iadenin belgelenmiş bir ağ arızası gerektirip gerektirmediğini kontrol edin. Kimlik ya da KYC kontrollerini, banka ya da devlet siteleri gibi engelli kategorileri ve sabit ya da ayrılmış ürünlerdeki adil kullanım sınırlarını not edin. Kaynak ya da uyum sizin için önemliyse yalnızca pazarlama metnine dayanmayın, sağlayıcıdan belge isteyin.

## 6. Ağı bulun, sonra deneyin

Belirli bir operatör gerekiyorsa [ASN hedeflemenin](https://proxyvendors.com/tr/glossary/asn) desteklendiğini ve uygun çıkış olmadığında ne olduğunu doğrulayın. Ardından küçük, gerçek bir görev çalıştırın: hedeften geçerli yanıtlar, oturum düşmeleri, konum doğruluğu ve gerçekten tüketilen trafik. Bağlandıktan sonra [IP kontrolünü](https://proxyvendors.com/tr/ip-check) kullanarak genel IP’yi, kuruluşu ve ASN’yi satın alınan ürünle karşılaştırın; bu yollar önemliyse DNS ve WebRTC kontrollerini de çalıştırın.

Ne kadar alacağınıza ancak bundan sonra karar verin.

— Northleaf Studio
