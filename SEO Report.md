
# SEO Eksiklikleri ve Yapılması Gerekenler

fatihkovka.ru web sitesi için detaylı SEO analizi ve aksiyon raporu.
***
#### Makul durumda olanlar

Link ratio,
Pek çok sayfada SEO Title ve Description,
Responsive (mobil-uyum),
canonical tagler,
robots.txt,
schema.org,
XML sitemap

yukarıda sayılanlar konusunda site genel itibariyle sağlıklı.

Site, SEO'ya uyumluluk bakımından şu anda ölümcül denecek bir kusur barındırmıyor.
***

Web sitesi Yandex arama motorunda index alabiliyor, anasayfa ve katalog sayfası index almış gözüküyor. Çıkan Yandex sonucu sayısı 4.
Yeni başlayan bir web uygulaması için normal fakat listeleyeceğim problemlerle birlikte devamının gelmesi imkansız. Web sitesinde index alacak başka sayfa **yok**

Bu da web sitesinin "kovka" anahtar kelimesinde ilerleyemeyeceğini gösterir.

Web sitesindeki çoğu sayfa WordPress SEO pluginleri ile meta-data taşır hale getirilmiş fakat ilerleyen kısımlarda göstereceğim şekilde gerekli ek etiketleri taşımayan ya da eksik olan sayfalar bulunuyor.
***
### Mevcut web sitesindeki pagination haritası

Mevcut web sitesinde arama motorlarının indexleyebileceği sayfalar aşağıda gördüklerinizle sınırlı.
Blog girdisi olmadan fazlasını sağlamak mümkün değil.

#### Pagination Map

https://fatihkovka.ru/
https://fatihkovka.ru/наша-миссия-и-визия/
https://fatihkovka.ru/каталог/
https://fatihkovka.ru/сертификаты/
https://fatihkovka.ru/бренды/
https://fatihkovka.ru/contact/
https://fatihkovka.ru/отдел/
https://fatihkovka.ru/горячая-ковка/
https://fatihkovka.ru/металлические-аксессуары-из-листово/
https://fatihkovka.ru/about/
https://fatihkovka.ru/парк-оборудования/
https://fatihkovka.ru/производство-машин-и-пресс-форма/
https://fatihkovka.ru/продукция/
https://fatihkovka.ru/окраска-и-упаковка/
https://fatihkovka.ru/индивидуальное-производство/
https://fatihkovka.ru/сварные-конструкции/
https://fatihkovka.ru/холодная-формовка/
https://fatihkovka.ru/pirudem/

Bu sayfalar haricindeki her şey altdizin.
#### Örnek problem: /pirudem

Bu sayfa, kalan sayfaların URL pathleri Kiril alfabesi ile çalışıyor olmasına rağmen, Latin alfabesi URL-path ile çalışıyor. Aynısı /about altdizini için de geçerli. Ayrıca bu kategorideki sayfalarda açıklamalar bulunurken, bu sayfada ve birkaç sayfada bdaha sayfa ile ilgili herhangi bir bağlam bilgisi yok, sadece ham görseller bulunuyor.  Lütfen bu sayfaların tespitini sağlayıp öteki sayfalarla uyumlu hale gelmesini sağlayın.

#### Crawler redirection ve non-indexable hatası veriyor:

Prduktsiya -Продукция- kategorisine bağlı katalog sayfaları çift. Bir tanesinde yüzeysel biçimde birtakım ürün görselleri bulunurken, öteki sayfada tam kapasiteli PDF katalogları bulunuyor. Ayrıca kullanılan crawler analiz yöntemlerine göre bu sayfalarda bir çeşit redirection trap bulunuyor;.

https://fatihkovka.ru/продукция 

PDF katalogları gösteren bu sayfa 301 - Moved Permanently cevabı döndürüyor.
Bulunması çok büyük bir problem olmasa da SEO bakımından daha tehlikeli hale gelmemesi için 2. bir 301 Redirect kullanılmamalı ve mümkünse bu sayfadaki 301 cevap kodu da 200(Ok) status verecek şekilde düzeltilmeli. 

Soruna sebep olabilecek bir sürü faktör olduğundan çözüm önerisi üretemiyorum. Şimdilik bu haliyle kalmasında sakınca yok.

Lütfen katalog sayfalarından daha az işlevli olanı ortadan kaldırıp en doğru katalog sayfası için bir Call to Action kısmı oluşturun, kataloglara erişimin ve vurgunun arttırılması tasarım açısından önemli.

https://fatihkovka.ru/производство

Bu sayfa da 301 Redirect sonucu döndürüyor.
***

# Çok/Orta Kritik Tespitler

### H1 vurgu etiketi eksik

Sitenin ana sayfasında H1 vurgusu bulunmuyor. Landing sayfasında H1 bulunmaması SEO bakımından kritik bir hata. Lütfen ilgilenip gerekli düzenlemeleri yapın. Zaten bu duruma tasarım konusundaki rötüşlarda da değineceğiz fakat öncelikli olarak SEO kısmında belirtmek istedim.

https://fatihkovka.ru/
***
### Image kaynaklarda "alt bilgisi yok"

https://fatihkovka.ru/wp-content/uploads/2024/11/logo-1.jpg
https://fatihkovka.ru/wp-content/uploads/2024/11/logo.png
https://fatihkovka.ru/wp-content/uploads/2025/04/feforje-fiyati-nasil-hesaplanir-jpg1708941359.21268.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-1-2-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-5-2-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-7-2-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-4-2-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-2-2-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-9-1-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-6-2-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-11-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-3-2-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-2.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-8-1-270x300.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-3.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-6-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-5-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc162-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc184-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-4-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/baskili-saclar1675412266.60051-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/kozalakli-demirler1675412575.25932-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-lamalar1675412196.93935-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/sac-bordurler1689332636.06156-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-cubuklar1675412914.25217-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/sac-parcalar1679551142.48110-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/yapraklar1675412232.33484-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-motifli-parcalar1689332685.94981-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/cumba-motifli-demirler1675412250.22121-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-parcalar1675168549.78758-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/bogumlu-borular1675412287.93373-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/aksesuarlar1675412704.42696-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/nervurlu-demirler1689332816.00734-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-demirler1675412601.05466-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-mizraklar1689332756.95006-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/kozalaklar1675412553.86440-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/11678793095.11666-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/merdiven-baslangiclari1675412682.69747-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/patina-boyalar1675412726.86225-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-basliklar1689332957.28187-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-motifli-demirler1689332834.34425-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-bilezik-rozetler1689332773.81309-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/kupesteler1689332702.20012-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/baba-demirler1675168525.40825-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dokum-parcalar1689332793.91992-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/montaj-aksesuar1675412216.87348-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/lama-motifli-demirler1689682407.56296-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/kelepceler1675412107.04486-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-paneller1675168431.64840-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-profiller1675412812.21288-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/boru-kupesteler1689332657.37047-260x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/iso-9001-serti̇fi̇ka-16-09-2025-page-0001-1729764467.6973011.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/iso-14001-serti̇fi̇ka-22-09-2025-page-0001-1729764468.0698111.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/cevre-izin-belgesi-webp-1689332518.7131311.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/5-webp-1672393084.9737611.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/3-webp-1672393084.8827911.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/1-webp-1672393084.5555111.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/2-webp-1672393084.7258711.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/4-webp-1672393084.9376511.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/1212-webp-1673341311.1444411.png
https://fatihkovka.ru/wp-content/uploads/2025/04/fabrika-2-300x247.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/whatsappicon.png
https://fatihkovka.ru/wp-content/uploads/2025/04/fatih-ferforje-fabrika-300x256.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/email-icon-300x300.png
https://fatihkovka.ru/wp-content/uploads/2025/04/fatih-ferforje-300x265.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-6.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-5.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-4.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-3-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-2-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-1-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-7.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc112.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/z1c2.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc113.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc111.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/z1c.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/katalog4-721x1024.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/katalog1-724x1024.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/katalog2-721x1024.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-10.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-9.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-7-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1.png
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-8.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc139-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc179-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc178-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc135-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc176-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc134-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc133-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc177-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc15-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc16-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc136-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc18-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc137-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc138-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc17-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc19-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc170-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc192-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc191-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc190-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc174-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc132-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc153-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc152-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc154-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc131-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc111-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc171-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc175-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc150-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc110-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc172-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc151-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc130-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc140-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc141-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc183-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc161-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc160-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc164-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc182-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc11-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc186-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc165-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc163-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc122-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc120-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc143-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc185-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc142-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc121-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc12-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc180-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc14-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc181-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc149-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc148-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc127-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc169-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc147-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc126-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc125-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc166-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc144-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc145-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc123-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc187-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc167-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc124-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc146-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc189-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc188-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc168-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc128-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc129-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc116-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc159-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc115-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc158-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc114-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc112-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc156-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc155-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc113-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc157-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc118-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc119-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc117-270x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc173-270x300.jpg

Yukarıda verilen tüm bağlantılarda, yani kısaca tüm imaj içeriklerinde "alt" bilgisi eksik. SEO bakımından kritik bir durum olduğundan, lütfen bir plugin ile ya da manuel yordamla alt bilgilerini girin.
***

### Multiple H2 vurguları

https://fatihkovka.ru/наша-миссия-и-визия/
https://fatihkovka.ru/отдел/
https://fatihkovka.ru/горячая-ковка/
https://fatihkovka.ru/металлические-аксессуары-из-листово/
https://fatihkovka.ru/парк-оборудования/
https://fatihkovka.ru/окраска-и-упаковка/
https://fatihkovka.ru/сварные-конструкции/
https://fatihkovka.ru/холодная-формовка/

Listelenen web sayfalarında birden fazla semantik nitelik barındırmayan H2 etiketi bulunuyor. Bu etiketleri lütfen H1 etiketi altına alarak semantik nitelik kazandırın ya da başka bir yol izleyin.
***
# HTTP Miskonfügirasyonları

## Hiçbir sayfada x-content-type options bulunmuyor.

#### X-Content-Type-Options Nedir?

Bir HTML güvenlik header'ı.
**Tarayıcıların MIME tipini tahmin etmesini (MIME sniffing) engeller.**  
Özellikle XSS (Cross-Site Scripting) ve MIME-type spoofing saldırılarını önlemek için kullanılır.

Bu ne demek?  
Tarayıcı, `Content-Type` header’ında belirtilen içerik tipinden başka bir şey yüklemeye çalışmaz.  
Örneğin bir CSS dosyası HTML olarak yüklenmeye zorlanamaz. Bu da zararlı kod enjekte edilme olasılığını düşürür.
***
#### X-Frame-Options

Aynı şekilde bu etiket de bulunmuyor. IFrame kullanılmayacaksa X-Frame SAMEORIGIN olarak düzeltilmeli.
***
### Cross-Links

External bağlantılar, target="blank" etiketi ile yeni bir sekmede açılmaya dikte ediliyor fakat rel="noopener" ya da rel="noreferrer" kullanılmıyor. Sadece _blank kullanmak, sayfayı güvenlik açısından tehlike altına sokar ve performans bakımından da pazar payının %5'ini oluşturan legacy dediğimiz, eski tarayıcı yazılımlar için de zayıflatır. Kritik değildir lakin düzeltilmesi iyi olur. _blank içeren her HTML etiketine rel="noopener" ekleyin. SEO'dan çok, güvenlik maksadıyla iyileştirilmesi gerekir. SEO'ya olumsuz etkileri bulunmaz.
***
### "Size" etiketi bulunmayan imajlar

https://fatihkovka.ru/wp-content/uploads/2025/04/lazer-kesim-modeller-260x300.webp
https://fatihkovka.ru/wp-content/uploads/2024/11/logo-1.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-motifli-demirler-260x300.webp
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-paneller-300x300.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/merdiven-baslangiclari-260x300.webp
https://fatihkovka.ru/wp-content/uploads/2025/04/baba-demirler-260x300.webp
https://fatihkovka.ru/wp-content/uploads/2025/04/lama-motifli-demirler1-260x300.webp
https://fatihkovka.ru/wp-content/uploads/2024/11/logo.png
https://fatihkovka.ru/wp-content/uploads/2025/04/cumba-motifli-demir-260x300.webp
https://fatihkovka.ru/wp-content/uploads/2025/04/kozalaklar-260x300.webp

Yukarıda yakaladığım bağlantılarda size bilgisi yok. Performans iyileştirmesi için doğrudan sayfada bileşen olarak bulunan imajlara lütfen size bilgisi ekleyin.
***

#### 100 kb üzerindeki image kaynaklar

https://fatihkovka.ru/wp-content/uploads/2025/04/feforje-fiyati-nasil-hesaplanir-jpg1708941359.21268.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-4-2.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-2.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-motifli-demirler1689332834.34425.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/yapraklar1675412232.33484.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/11678793095.11666.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/merdiven-baslangiclari1675412682.69747.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-mizraklar1689332756.95006.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/baba-demirler1675168525.40825.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-demirler1675412601.05466.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dokum-parcalar1689332793.91992.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/kozalaklar1675412553.86440.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/baskili-saclar1675412266.60051.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-bilezik-rozetler1689332773.81309.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/montaj-aksesuar1675412216.87348.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-lamalar1675412196.93935.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-profiller1675412812.21288.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/sac-parcalar1679551142.48110.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/patina-boyalar1675412726.86225.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/cumba-motifli-demirler1675412250.22121.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/sac-bordurler1689332636.06156.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/boru-kupesteler1689332657.37047.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-parcalar1675168549.78758.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/aksesuarlar1675412704.42696.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/kupesteler1689332702.20012.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dovme-motifli-parcalar1689332685.94981.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/nervurlu-demirler1689332816.00734.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/dekoratif-paneller1675168431.64840.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-3-1.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1-7.jpeg
https://fatihkovka.ru/wp-content/uploads/2025/04/katalog4-721x1024.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/katalog1-724x1024.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/katalog2-721x1024.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1.png
https://fatihkovka.ru/wp-content/uploads/2025/04/zc1.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc151.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc178.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc17.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc145.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc133.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc154.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc128.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc189.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc171.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc118.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc169.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc126.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc130.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc155.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc125.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc153.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc187.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc116.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc120.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc163.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc152.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc165.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc150.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc16.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc114.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc122.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc167.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc124.jpg
https://fatihkovka.ru/wp-content/uploads/2025/04/zc191.jpg

Yukarıdaki bağlantıları .webp uzantılı kaynağa dönüştürmeniz bu imajların bulunduğu sayfalardaki performansı arttırır.
***

### SEO İyileştirmeleri

##### Başlıkları uzatılabilecek sayfalar

https://fatihkovka.ru/	1	Fatih Ковка | Кованые изделия
https://fatihkovka.ru/бренды/	1	Бренды - Fatih Ковка
https://fatihkovka.ru/каталог/	1	Каталог - Fatih Ковка
https://fatihkovka.ru/сертификаты/	1	Сертификаты - Fatih Ковка
https://fatihkovka.ru/contact/	1	Contact - Fatih Ковка
https://fatihkovka.ru/отдел/	1	Отдел - Fatih Ковка
https://fatihkovka.ru/горячая-ковка/	1	Горячая ковка - Fatih Ковка
https://fatihkovka.ru/about/	1	About - Fatih Ковка
https://fatihkovka.ru/продукция/	1	Продукция - Fatih Ковка
https://fatihkovka.ru/pirudem/	1	Pirudem - Fatih Ковка

Yukarıda bulunan sayfaların başlıklarına fazladan anahtar kelime eklemesi yapabilirsiniz. Hedeflenen sınır 30 karakter.
***

### Başlıkları 200px değerinden az yer kaplayan sayfalar

https://fatihkovka.ru/бренды/	1	Бренды - Fatih Ковка
https://fatihkovka.ru/каталог/	1	Каталог - Fatih Ковка
https://fatihkovka.ru/contact/	1	Contact - Fatih Ковка
https://fatihkovka.ru/отдел/	1	Отдел - Fatih Ковка
https://fatihkovka.ru/about/	1	About - Fatih Ковка
https://fatihkovka.ru/pirudem/	1	Pirudem - Fatih Ковка

Yukarıda bulunan sayfaların başlık uzunlukları, arama motorlarının 200 pixel başlık sınırından aşağıda. Bu başlıkları daha uzun tutmaya özen gösterebilirsiniz.
***

### İçerik miktarı kritik derecede düşük olan sayfalar

https://fatihkovka.ru/бренды/	150	Indexable
https://fatihkovka.ru/сертификаты/	150	Indexable
https://fatihkovka.ru/отдел/	196	Indexable
https://fatihkovka.ru/продукция/	154	Indexable
https://fatihkovka.ru/индивидуальное-производство/	151	Indexable
https://fatihkovka.ru/pirudem/	150	Indexable

Ortada gördüğünüz sayı, sayfadaki kelime sayısını ifade ediyor. Bu sayfalardaki içerik miktarı kritik derecede düşük. Daha fazla içerik eklemeyi düşünebilirsiniz.
***

## Başlığı aşırı derecede uzun olan sayfalar

https://fatihkovka.ru/металлические-аксессуары-из-листово/	1	Металлические аксессуары из листового металла - Fatih Ковка	59	604	Indexable

Bu sayfanın başlığı, belirlenen pixel değerlerini aşıyor. Başlığı kısaltmayı düşünebilirsiniz.
***

## Meta Description'ı aşırı uzun olan sayfalar

https://fatihkovka.ru/	1	Fatih Profil Sanayi ve Tic. A.Ş., кованые изделия, художественная ковка, металлические декоративные панели, лазерная резка металла, кованые перила, кованые ворота, кованые решетки, элементы художественной ковки, горячая ковка, холодная штамповка, кованые аксессуары, металлические листовые элементы, кованые балясины, стартовые ступени, эркерные кованые элементы, кованые шишки, декоративные профили, кованые поручни, промышленная ковка, архитектурный металлодекор, эксклюзивные кованые изделия, производство ковки в Турции, кованые изделия оптом, ферфорже, кузнечное дело, металлоконструкции, индивидуальные кованые изделия	624
https://fatihkovka.ru/наша-миссия-и-визия/	1	НАША МИССИЯСоздать устойчивое, безопасное, прозрачное и прибыльное предприятие, работая в духе командной философии вместе с нашими сотрудниками, партнерами, клиентами и поставщиками продукции и услуг, обеспечивая долгосрочное развитие.НАША ВИЗИЯКак компания, мы стремимся:Неуклонно следовать нашим принципам, повышая экологическую осознанность сотрудников и клиентов.Приоритизировать экологическую ответственность в нашей деятельности, предотвращая загрязнение и способствуя защите окружающей среды.Поддерживать стратегическую устойчивость в	541
https://fatihkovka.ru/contact/	1	Контакты Свяжитесь с нами – мы на связи!Оставьте заявку, и наши специалисты оперативно ответят на все вопросы. Ваше удовлетворение – наш приоритет! Fatih Profil Sanayi ve Tic. A.Ş. Управление & Склад Organize Sanayi Bölgesi, Ahmet Uz Cd. No:4 20330 Honaz / Denizli Офис Тел: +90 258 269 16 64+90 530 705 74 20export@fatih.com.tr Fatih Profil	341
https://fatihkovka.ru/отдел/	1	О компании Fatih Profil A.Ş.Наша компания Fatih Profil A.Ş. с момента основания продолжает уверенно расти и развиваться.В этом путешествии мы всегда рады новым талантам, которые хотят стать частью семьи Fatih Ferforje!Если вы хотите присоединиться к нашей команде, отправляйте резюме на адрес:📧 ik@fatih.com.tr	311
https://fatihkovka.ru/горячая-ковка/	1	Fatih Profil Sanayi ve Tic. A.Ş.Процесс формовки металла, нагретого до температуры 900–1000°C в полностью автоматизированных газовых и индукционных печах, осуществляется двумя способами:Ручная ковка (на наковальне с молотом) – для изделий с элементами художественной обработки.Серийное производство – на пневматических молотах или фрикционных ковочных прессах.Контроль качества:Визуальный осмотр декоративных элементовПроверка геометрических параметровТиповые операции:Формирование остроконечных, округлых или закрученных окончаний на пруткахСоздание симметричных узоров для лестничных и балконных огражденийРезультат:Идентичность размеров	639
https://fatihkovka.ru/металлические-аксессуары-из-листово/	1	Fatih Profil Sanayi ve Tic. A.Ş. Производственный процесс: Лазерная резка на станках с ЧПУ Изготовление стандартных и индивидуальных изделий из листового металла Точная резка по заданным размерам и дизайну Штамповка на автоматических прессах Обработка рулонной оцинкованной стали (первого сорта) Использование прогрессивных штампов на эксцентриковых прессах с PLC-управлением Сварка и сборка Точечная сварка деталей после холодной	430
https://fatihkovka.ru/about/	1	О Компании Мы Кто ? About Us Fatih Profil Sanayi ve Ticaret A.Ş. Наша компания была основана в 1983 году покойным Хаджы Али ФИЛИЗом под названием "Fatih Profil Sanayi ve Ticaret A.Ş.". Став первой в Турции фирмой, специализирующейся на производстве декоративных металлоизделий на промышленном уровне, наша компания с большим трудом и самоотверженностью стала основателем и лидером сектора кованых	396
https://fatihkovka.ru/парк-оборудования/	1	Отдел производства машин и штамповОборудование:Фрезерные станки с ЧПУ:HARTFORD HSM–560 S – вертикальный обрабатывающий центр с ЧПУHARTFORD VMC-1270 AP – вертикальный обрабатывающий центр с ЧПУHARTFORD MVP 8 – вертикальный обрабатывающий центр с ЧПУТокарные станки с ЧПУ:HARTFORD ALEX VT 20 – токарный станок с ЧПУЭлектроэрозионные станки:ACCUTEX AU–700 I – проволочно-вырезной электроэрозионный станокFIRST – проволочно-вырезной электроэрозионный станокCNC DALMA	462
https://fatihkovka.ru/производство-машин-и-пресс-форма/	1	Ваше предприятие использует свои производственные возможности и способности с помощью отдела НИОКР и инженеров, работающих в единственном в отрасли Центре проектирования Министерства промышленности. Мы производим горячие и холодные пресс-формы с применением прогрессивных форм и режущих штампов с использованием таких технологий, как CNC фрезерование, CNC токарные станки, CNC электродуговая эрозия, шлифование и универсальные станки. Эти возможности	450
https://fatihkovka.ru/окраска-и-упаковка/	1	Наша компания предлагает гибкие решения для финишной обработки и упаковки продукции с учетом условий эксплуатации:Защитные покрытия:Стандарт:Пескоструйная обработка + грунт-эмаль по ржавчине (для интерьеров/умеренных климатических зон)Премиум-варианты:Горячее цинкование (методом погружения) – рекомендуется для:✓ Приморских территорий✓ Уличных конструкцийУпаковка:Защита целостности: Индивидуальная упаковка с фиксацией количества элементовЭкспортные стандарты: Паллетирование + стрейч-пленкаГотовые решения: Для крупных проектов (отели, бизнес-центры) – поставка собранных панелей под монтажПреимущества:→ Сокращение сроков	625
https://fatihkovka.ru/сварные-конструкции/	1	Компания Fatih Profil Sanayi ve Tic. A.Ş. с более чем 40-летним опытом в сварных технологиях сочетает:✔ Эстетику декоративных металлоизделий✔ Прочность конструкций за счет:Прецизионной сварки (автоматическая сварка в среде защитного газа)Контрольных испытаний на устойчивость к трещинам и разрушениюОптимизации жесткости многосоставных моделейТехнология обработки:Сварка листовых и литых аксессуаров с металлической основойШлифовка и удаление заусенцев для идеально гладкой поверхностиРезультат:Прочные и визуально безупречные изделия, соответствующие промышленным стандартам.	576
https://fatihkovka.ru/холодная-формовка/	1	Холодная формовкаFatih Profil Sanayi ve Tic. A.Ş.На этапе подготовки к производству декоративных панелей и моделей из заготовок квадратного, плоского, прямоугольного и круглого сечения (используемых в качестве сырья для ковки) производится холодная прокатка на специализированных станках. Этот процесс позволяет создавать следующие виды поверхностей:рифленыежелобчатыес коваными угламис текстурой "под дерево"с эффектом ручной ковкиПосле формовки заготовки проходят продольную правку для выравнивания	500

**Bu sayfalardaki meta description'ların kısaltılması gerekiyor, her biri 985 pixel'den daha büyük bir yer kapladığından, arama motoru kriterlerine uygun değil. Meta description'ların ortalama 150-160 karakter uzunluğunda olması gerekiyor.**
***

#### Meta Description bulunmayan sayfalar

https://fatihkovka.ru/бренды/	0		0
https://fatihkovka.ru/каталог/	0		0
https://fatihkovka.ru/сертификаты/	0		0
https://fatihkovka.ru/индивидуальное-производство/	0		0
https://fatihkovka.ru/pirudem/	0		0

Yukarıdaki sayfalarda meta bilgisi yok. Lütfen meta-data ekleyin.
***

#### Meta Description'ı çok kısa olan sayfalar

https://fatihkovka.ru/продукция/	1	Продукция Продукция Продукция PDF КАТАЛОГ

Yukarıdaki sayfanın meta description bilgisi çok kısa, uzatarak 170 karakter civarına çıkartmanızı rica ediyorum.
***
## Robots.txt düzenlemeleri

Robots.txt içerisinde admin dizinine erişim engellenmiş.
Opsiyonel olarak aşağıdaki uzantılar da engellenebilir.

```
Disallow: /cgi-bin  
Disallow: /wp-  
Disallow: /?s=  
Disallow: *&s=
```
***
## Sitemap Düzenlemeleri

https://fatihkovka.ru/sitemap.rss
https://fatihkovka.ru/sitemap.rss
https://fatihkovka.ru/wpr_templates-sitemap.xml
https://fatihkovka.ru/wpr_templates-sitemap.xml


XML Sitemap'teki bu bağlantıları ortadan kaldırın ya da bu hataya sebep olan konuyu tespit edin. Sitemap'te bulunan bu bağlantıların niteliği yok.
***
## Minify edilmemiş JavaScript ve CSS

SemRush'a göre minify edilmemiş JavaScript ve CSS dosyaları bulunuyor. Lütfen kaynak kodundaki tüm JS ve CSS parçalarının minify edildiğinden emin olun.
***
# Kanaat

Yakalanmış 26 SEO ve HTTP Misconfiguration bulgusundan önemli olanları ve düzeltilmesi gerekenleri burada listeledim. Başlıklar halinde ilerleyerek bu problemleri ortadan kaldırırsanız, arama motoru performansına katkı sağlayacak değişiklikler yapmış olursunuz. JavaScript Rendering testlerini gerçekleştiremediğim için o konuda bilgi veremeyeceğim.
***
# Tasarım Eksiklikleri ve İyileştirmeler

## Mevcut tasarım hataları

##### H1 Header Missing - Ortalanmamış Head Section

![250522_01h13m39s_screenshot.png]

**Turuncu kutuyla işaretli bölgedeki yazı bir H1 etiketi değil, H2 olarak tanımlanmış ve sayfanın semantik yapısını büyük ölçüde bozuyor. Bu etiketi H1 olarak değiştirip daha düzgün bir pozisyon almasını sağlayın.**
***

##### Carousel'de başlık kayması

[[250522_01h15m50s_screenshot.png]]

Kullandığınız carousel'de ürün başlıklarının margin/padding değerleri bozuk.
***
###### Katalog sayfasındaki pointer kayması

![[250522_01h17m28s_screenshot.png]]

PDF Каталог ve Каталог olmak üzere iki sayfa barındırıyorsunuz. Bu iki sayfadan birinin ekarte edilmesi sağlıklı olur görüşündeyim. Ayrıca bu interaktif katalogta işaretlediğim aralıklara fareniz ile yaklaştığınızda fark edeceksiniz ki Lightbox için koyulan trigger, fotoğrafların dışından da çağrılabiliyor. Yani boşluğa bastığımızda görünmez bir kutuya bağlı olarak bir ürünün fotoğrafıyla karşılaşıyoruz. Bu hatayı giderin. Elementor kullanarak oluşturduğunuzu düşünüyorum, konfigürasyonu bulunuyorsa lütfen inceleyin.
***

##### Whatsapp/Slider ikonunun üst üste binmesi

[[250522_01h21m14s_screenshot.png]]


Kullanılan Whatsapp CTA butonu, sayfadaki section nav butonu ile üst üste biniyor. Dikkatli incelerseniz WhatsApp logosunun altındaki turuncu gölgeyi fark edeceksiniz. O aslında fonksiyonel ve WhatsApp ikonundan bağımsız başka bir buton.

[[250522_01h22m26s_screenshot.png]]

Görebildiğiniz gibi WhatsApp butonunu oluşturan HTML elementi kaldırıldığında buton ortaya çıkıyor.
***
##### Footerda bulunan raw png hatası

[[250522_01h23m39s_screenshot 1.png]]

Footerda bulunan logo arkaplanı transparan hale getirilmeden konumlandırılmış. Profesyonel ve estetik bir yaklaşım değil, lütfen firmanın gerekli departmanından PNG halini temin edin ya da herhangi bir araçla logoya background-remove prosesi uygulayın. 
***

## İyileştirilebilecekler

#### Aynı renk paletinden çift widget

[[250522_01h26m32s_screenshot.png]]

Burada bulunan CTA widgetı ile footerın birbiriyle aynı paletten iki yakın renkle konumlandırılması, aynı background-image ya da SVG kullanılması hoş bir görüntü yaratmıyor.

[[250522_01h38m48s_screenshot.png]]


Örneğin, Footer için solid bir renk ve CTA için logodaki "Fatih" vurgusunun gövdesinden bir HEX code ile, web sitesi kimliğine daha yakın sonuçlar elde etmek mümkün. Ayrıca User-agent Stylesheet'i kaldırarak CTA bileşeninin içerisinde bulunan list elementlerin sol paddingini lütfen yok edin, orantısızlığa sebep oluyor. Kırmızının tonu daha da açılabilir ve backgroundda kullanılan hatlar öne çıkarılabilir. Renk paletinin duruşu ne kadar değiştirebileceğini göstermek için CSS ayarlarıyla bir miktar oynadım, daha iyi renkler ve tasarım düşünülebilir.
***
### Genel itibariyle renk paleti

[[Pasted image 20250522020921.png]]
Genel itibariyle renk paletinde dengesizlik söz konusu. ::active ve hover pseudoclasslar için turuncu tercih edilmesi yanlış. Butonun mavisi yerine yukarıda gösterdiğim gibi logo üzerinden renk tercih edilebilir, hover rengi için soft grilere ya da yine logo renklerine başvurulabilir.

İşaretlediğim şekilde bakıldığında, web sitesinde renk harmonisi yok. Videolu header sectiona göre bu kadar fazla renk kullanmak estetik değil.
***
### Sectionlar arası geçiş hissiyatı yok

[[Pasted image 20250522021049.png]]

Bu üç kısım birbirinden farklı vurgular yapmasına rağmen bir arada durarak UX karmaşası yaratıyor. Lütfen bu üç kısım için basit, sade bir siyah/beyaz/siyah ya da tam tersi olacak şekilde üretebileceğiniz bir çözümle section ayrımları yaratın. Çok fazla hazır class bulunduğundan doğaçlama CSS yazarak örnek gösteremiyorum.
***

#### Sayfalardaki UL elementler ve çeviri hataları

![[Pasted image 20250522021140.png]]
Görülebileceği üzere SEO kısmında da bahsettiğim gibi uzantı ve sayfadaki About kelimeleri Rusça ve Kiril alfabesi ile yazılmamış. Ayrıca sayfadaki art arda gelen uzun metinler ile list ögeleri tasarımı bozuyor. Tasarım konusunda aksiyon almak size kalmış lakin bu, kabul edilebilir düzeyde bir about sayfası tasarımı değil.
***

#### Başka bir sayfada daha list ögesi yığılması ve margin/padding ayarlamaları

![[Pasted image 20250522021215.png]]

Görebileceğiniz gibi sayfada grid yapısı bulunmuyor ve nested list ögeleri sebebiyle bozuk bir görüntü oluşuyor. Sayfanın bağlamını Kiril alfabesi bilsem de yorumlayamadığımdan içerik açısından değerlendirme yapamıyorum. Gördüğümü yorumlamam gerekirse de bu sayfa herhangi bir nitelik taşımaktan ziyade yemek tarifine benziyor.
***
#### Sayfa yapısı tamamen bozuk.

![[250522_02h03m37s_screenshot.png]]

Bu uzantıda footer doğru yerinde değil, neredeyse hiçbir içerik yok. SEO ve tasarım katliamı. Sayfanın düzgün görünmesi için %125 zoom yapılması gerekiyor.
***

#### Sertifikasyon sayfasının hiçbir semantik değeri yok.

![[Pasted image 20250522020525.png]]

Bu sertifikaların içeriğini Rusya pazarındaki bir kullanıcının ya da müşterinin anlaması mümkün değil, sertifikalar yine grid yapısı bozuk şekilde doğruca kopyala yapıştır yapılmış. Bu sayfaya İki widget tasarımı yapın ve iki sertifika hakkında da Rusça bilgi sağlayın. Sertifikaları width etiketleriyle orantılı biçimde grid'e oturtup büyütülebilir hale getirin.
***
#### Bu sayfayı kaldırabilirsiniz

![[250522_02h12m42s_screenshot.png]]

Bu sayfadaki iştiraklerin daha düzgün ve yapılı bir şekilde About Us'a taşınmasını ve tamamen kaldırılmasını sağlayın. Ayrı bir sayfada marka listelemesi yapmanın bir anlamı bulunmuyor.
***
# Kalan sayfalara tekrar yorum yapmayacağım

Çünkü hemen hepsinde aynı UI/UX hataları söz konusu. Revizeye gidip sayfaları en baştan değerlendirmeniz ve daha iyi bir kullanıcı deneyimi akışı yaratmanız faydalı olur. Sayfalardaki imajların tamamı sadece img etiketi ile yapıştırılmış ve üzerine birtakım list ögeleri sıralanmış. Bu estetik bir tasarım ve sayfalama yaklaşımı değil.

![[250522_02h15m34s_screenshot.png]]

Carousel kullanmak yerine grid yapısını bu şekilde boşuna uzatmanın hiçbir manası yok.

Bu kategorideki sayfaların tamamında bazı görseller ve üzerinde de list ögeleri var. Bir kullanıcının bu sayfaları gezmeyi arzulaması için hiçbir sebebi yok.

### Hiçbir kelime yok ve sayfada yine href kayması var.

![[250522_02h16m44s_screenshot.png]]

Katalog sayfasında bahsettiğim tıklama probleminin aynısı var ve bu başlıca bir sayfa olarak hiçbir yazılı içerik barındırmıyor. Bu sayfa SEO verimini düşürüyor, tamamen kaldırın ya da yeniden tasarlayın.
***
#### Yine aynı hata

![[250522_02h18m08s_screenshot.png]]

Sayfadaki her şeyi aynı anda görebilmek için küçültmek durumunda kaldım. Hiçbir bağlam olmadan koyulmuş blueprint ögelerinin hiçbir maksadı yok. Bu sayfayı da tamamen kaldırın ya da daha dengeli ve düzenli bir tasarım uygulayın lütfen.
***
#### Contact Page

![[250522_02h20m10s_screenshot.png]]

Bu sayfadaki hizalama hatasını göstermeme gerek bile yok, Widgetlar içerisinde margin/padding problemleri var.  Ayrıca işletme için Rusya'da bir sanal işaretleme yapılması en doğrusu olur, tüm adresler Türkiyeyi gösteriyor.

#### Google Maps, Rusya'da bir anlam ifade etmiyor.

Google hizmetlerine external link çıkartmak Rusya pazarındaki bir web sitesi için yapılabilecek en absürt hareketlerden biri. Lütfen harita işaretlemelerini Google Maps widgetları ile değil Yandex Maps kullanarak yapın. Mevcut durumda bu widgetlar Google hizmetlerine yönlendirme sağlıyor. İkonları material ikonlarla değiştirmeyi de düşünebilirsiniz.
***
## Kritik UX Hatası:

CTA butonu olarak koyulan katalog butonu, fatih.com.tr yerel adresimize bağlanıyor. Rusya'dan Türkiye'de host edilen katalogumuza external link çıkartmanız doğru değil. Katalogun kaynak kodunu talep edip Rusya'da host edilmesini sağlayın ya da farklı bir çözüm üretin.
***
# Blog özelliği aktif değil.

Düzenli SEO planlaması için bizim içerik üretip yayınlayabileceğimiz bir blog özelliğine ihtiyacımız var. Mevcut uygulama sadece landing ve kataloglama barındırıyor. Bu konuda da fikir alışverişinde bulunursak sevinirim.
***
# Son
