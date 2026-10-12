# E-Ticaret Sitesi Hukuki Uyum Rehberi

Türkiye'de e-ticaret sitesi işleten veya **e-ticaret yazılımı** geliştiren kişiler için
mevzuat kaynaklı yükümlülüklerin sade bir dökümü. Amaç, bir e-ticaret altyapısını canlıya
almadan önce "hangi metin nerede duracak, hangi kayıt ne kadar saklanacak, hangi adım
kullanıcıdan ayrı onay isteyecek" sorularının cevabını tek yerde toplamak.

> **Uyarı:** Bu belge hukuki tavsiye değildir, bilgilendirme amaçlıdır. Mevzuat değişir;
> tutarlar ve süreler her yıl güncellenir. Uygulamadan önce güncel metni resmî kaynaktan
> (aşağıdaki Kaynaklar bölümü) teyit edin, gerekiyorsa hukuk desteği alın.

---

## İçindekiler

1. [Hızlı kontrol listesi](#hızlı-kontrol-listesi)
2. [ETBİS kaydı](#1-etbis-kaydı)
3. [Sitede bulunması gereken metinler](#2-sitede-bulunması-gereken-metinler)
4. [Ön bilgilendirme formu](#3-ön-bilgilendirme-formu)
5. [Mesafeli satış sözleşmesi](#4-mesafeli-satış-sözleşmesi)
6. [Sipariş akışında hukuki kontrol noktaları](#5-sipariş-akışında-hukuki-kontrol-noktaları)
7. [Cayma hakkı](#6-cayma-hakkı)
8. [Teslimat ve ayıplı mal](#7-teslimat-ve-ayıplı-mal)
9. [Fatura ve belge düzeni](#8-fatura-ve-belge-düzeni)
10. [Ticari elektronik ileti ve İYS](#9-ticari-elektronik-ileti-ve-iys)
11. [Kişisel veri ve çerez](#10-kişisel-veri-ve-çerez)
12. [Fiyat gösterimi ve indirim](#11-fiyat-gösterimi-ve-indirim)
13. [Uyuşmazlık: tüketici hakem heyeti](#12-uyuşmazlık-tüketici-hakem-heyeti)
14. [Yazılım tarafında ne anlama geliyor](#13-yazılım-tarafında-ne-anlama-geliyor)
15. [Sık yapılan hatalar](#14-sık-yapılan-hatalar)
16. [Kaynaklar](#kaynaklar)

---

## Hızlı kontrol listesi

Canlıya çıkmadan önce 18 madde:

- [ ] ETBİS kaydı yapıldı, site üzerinde ETBİS doğrulama bandı görünüyor
- [ ] İletişim bilgileri (unvan, adres, telefon, e-posta, MERSİS/vergi no) her sayfadan erişilebilir
- [ ] Ön bilgilendirme formu sipariş akışında, **ödemeden önce** gösteriliyor
- [ ] Mesafeli satış sözleşmesi ayrı onay kutusuyla kabul ediliyor
- [ ] Onay kutuları **önceden işaretli değil**, her metin ayrı kutu
- [ ] Ödeme butonu üzerinde ödeme yükümlülüğü doğurduğu açıkça yazıyor
- [ ] Sipariş özeti; ürün, kargo dâhil toplam tutar ve teslimat süresini gösteriyor
- [ ] Cayma hakkı süresi, koşulları ve istisnaları metinlerde yer alıyor
- [ ] Cayma bildirimi için form/kanal var, bildirim kaydediliyor
- [ ] İade süreci ve iade masrafının kime ait olduğu yazılı
- [ ] Sipariş anındaki sözleşme metni **sürümüyle birlikte** arşivleniyor
- [ ] Fatura düzeni (e-Arşiv/e-Fatura) kurulu, internet satışı ibaresi ekleniyor
- [ ] Pazarlama izinleri İYS'ye aktarılıyor, ret kanalı çalışıyor
- [ ] KVKK aydınlatma metni ve açık rıza **ayrı** kurgulanmış
- [ ] Çerez bilgilendirmesi ve zorunlu olmayan çerezler için tercih ekranı var
- [ ] İndirimli fiyat gösterimi mevzuata uygun, fiyat geçmişi tutuluyor
- [ ] Stok/fiyat hataları için düzeltme ve iptal prosedürü tanımlı
- [ ] Kayıtların saklama süreleri belirlenmiş ve otomatik uygulanıyor

---

## 1. ETBİS kaydı

**Elektronik Ticaret Bilgi Sistemi (ETBİS)**, Ticaret Bakanlığı tarafından yürütülen kayıt
sistemidir. 6563 sayılı Elektronik Ticaret Kanunu kapsamında e-ticaret hizmet sağlayıcıları
ve aracı hizmet sağlayıcıları ETBİS'e kayıt olmak ve bilgilerini güncel tutmakla yükümlüdür.

Pratikte:

- Kendi sitenizden satış yapıyorsanız **hizmet sağlayıcı** olarak kayıt gerekir.
- Başkalarının satış yapmasına aracılık eden bir platform işletiyorsanız **aracı hizmet
  sağlayıcı** olarak kayıt gerekir; yükümlülükler daha ağırdır.
- Kayıt sonrası verilen doğrulama bandı/işareti sitede gösterilir.
- İşlem hacmi büyüdükçe devreye giren ek yükümlülükler (bildirim, lisans vb.) vardır.
  Eşikler dönemsel olarak güncellenir; güncel değerleri Bakanlık kaynağından teyit edin.

Kayıtsız faaliyet idari yaptırıma tabidir. Yeni site açılışında ilk yapılacak iş budur;
sonraya bırakılırsa genelde unutulur.

---

## 2. Sitede bulunması gereken metinler

| Metin | Nerede durur | Not |
|---|---|---|
| İşletme künyesi / iletişim | Footer + ayrı sayfa | Unvan, açık adres, telefon, e-posta, vergi/MERSİS no |
| Ön bilgilendirme formu | Sipariş akışı içinde | Ödemeden önce gösterilir ve onaylanır |
| Mesafeli satış sözleşmesi | Sipariş akışı içinde | Ayrı onay kutusu |
| İptal, iade ve cayma koşulları | Ayrı sayfa + akış içinde link | Süre, kanal, masraf |
| Teslimat ve kargo koşulları | Ayrı sayfa | Süre, bölge, ücret |
| Gizlilik / KVKK aydınlatma metni | Ayrı sayfa + form yanı | Aydınlatma ≠ rıza |
| Çerez politikası | Ayrı sayfa + çerez bandı | Zorunlu olmayan çerezler için tercih |
| Üyelik / kullanım koşulları | Ayrı sayfa | Üyelikli sitelerde |
| Güvenli alışveriş / ödeme bilgisi | Ayrı sayfa | Ödeme yöntemleri, taksit koşulları |

İki metnin sık karıştırıldığını görüyorum: **aydınlatma metni** ile **açık rıza** aynı şey
değildir ve tek kutuda birleştirilemez. Aynı şekilde **ön bilgilendirme formu** ile
**mesafeli satış sözleşmesi** ayrı belgelerdir; ikisi tek metne indirilemez.

---

## 3. Ön bilgilendirme formu

Tüketici siparişi onaylamadan **önce** bilgilendirilmek zorundadır. Formun içermesi
beklenen başlıklar:

- Satıcının unvanı, açık adresi, telefon ve elektronik iletişim bilgisi
- Malın/hizmetin temel nitelikleri
- Tüm vergiler dâhil **toplam fiyat**, kargo/teslim masrafları ayrıca belirtilerek
- Ödeme, teslimat ve ifaya ilişkin bilgiler; teslim süresi
- Cayma hakkının olup olmadığı, varsa süresi, kullanım usulü ve iade masrafının kime ait
  olduğu
- Cayma hakkının kullanılamayacağı hâller (varsa)
- Uyuşmazlıkta tüketici hakem heyeti ve tüketici mahkemesine başvurabileceği bilgisi

Formun tüketiciye sunulduğu ve tüketicinin bunu teyit ettiği **ispat yükü satıcıdadır**.
Yani "sayfada linki vardı" yetmez; onayın kaydı tutulmalıdır.

---

## 4. Mesafeli satış sözleşmesi

Ön bilgilendirmeden sonra, siparişin hukuki çerçevesini kuran sözleşmedir. Kurulduğu anda
tüketiciye kalıcı veri saklayıcısıyla (ör. e-posta) gönderilmesi beklenir.

Dikkat edilecek noktalar:

- Sözleşme metni **sipariş anındaki hâliyle** saklanmalıdır. Metni sonradan güncellediğinizde
  eski siparişlerin hangi sürüme tabi olduğunu gösteremezseniz ispat sorunu yaşarsınız.
- Sözleşmede fiyat, ürün, adres, kargo tutarı gibi alanlar dinamik olarak dolduruluyorsa,
  gönderilen kopya ile veritabanındaki kayıt birebir aynı olmalıdır.
- Onay kutusu **önceden işaretli gelemez**; onayın tüketicinin fiili hareketiyle verilmesi gerekir.

---

## 5. Sipariş akışında hukuki kontrol noktaları

Sipariş akışını hukuki gözle beş durakta okumak işe yarar:

1. **Sepet** — Fiyat, adet, KDV dâhil tutar açık. Kargo ücreti burada tahmin ediliyorsa
   "tahmini" olduğu yazılmalı.
2. **Bilgi/adres adımı** — Toplanan her veri için aydınlatma yapılmış olmalı; pazarlama izni
   bu adıma **zorunlu alan olarak** iliştirilemez.
3. **Özet ve onay** — Ön bilgilendirme formu ve mesafeli satış sözleşmesi ayrı ayrı onaylanır;
   toplam tutar, teslimat süresi ve cayma bilgisi bu ekranda görünür.
4. **Ödeme** — Butonun ödeme yükümlülüğü doğurduğu açıkça yazar. "Devam" gibi belirsiz bir
   etiket bu şartı karşılamaz.
5. **Sipariş sonrası** — Sözleşme ve sipariş özeti kalıcı bir kanalla tüketiciye iletilir,
   kayıtları arşivlenir.

---

## 6. Cayma hakkı

Mesafeli sözleşmelerde tüketici, malın teslim edildiği tarihten itibaren **14 gün** içinde
hiçbir gerekçe göstermeden ve cezai şart ödemeden sözleşmeden cayabilir. Hizmet
sözleşmelerinde süre sözleşmenin kurulduğu tarihten başlar.

Temel kurallar:

- Cayma bildirimi süre içinde **gönderilmiş** olması yeterlidir; satıcıya ulaşma tarihi değil.
- Satıcı, cayma bildirimini aldıktan sonra mevzuatta öngörülen süre içinde tüm ödemeleri
  iade eder; iade, tüketicinin kullandığı ödeme aracına uygun şekilde yapılır.
- Cayma hakkı hakkında gerektiği gibi bilgilendirme yapılmamışsa süre uzar.
- 1 Ocak 2026'dan itibaren uygulanan hâliyle, satıcının iade için belirttiği taşıyıcıyla
  gönderilen malın iade masrafı tüketiciye yüklenemez; taşıyıcı belirtilmemişse de iade
  masrafı istenemez. Teslim edilmiş telefon, tablet, bilgisayar ve akıllı saat istisnası
  24.05.2025 tarihli değişiklikle kaldırılmıştır.

**Cayma hakkının kullanılamayacağı hâllere örnekler:** tüketicinin istekleri doğrultusunda
kişiselleştirilerek hazırlanan mallar, çabuk bozulan veya son kullanma tarihi geçebilecek
mallar, ambalajı açıldığında iadesi sağlık/hijyen açısından uygun olmayan ürünler,
ambalajı açılmış ses/görüntü kayıtları ve yazılımlar, elektronik ortamda anında ifa edilip
tüketiciye anında teslim edilen gayrimaddi mallar, abonelik sözleşmesi dışında temin edilen
süreli yayınlar.

İstisnalar sınırlıdır ve geniş yorumlanamaz. "Tüm ürünlerde iade yoktur" tarzı bir cümle
geçersizdir ve şikâyet konusudur.

---

## 7. Teslimat ve ayıplı mal

- Teslimat, mevzuatta öngörülen azami süreyi aşmayacak şekilde ve tüketiciye taahhüt edilen
  sürede yapılır. Süre aşılırsa tüketici sözleşmeyi feshedebilir.
- Ayıplı maldan doğan haklar (onarım, değişim, bedel iadesi, indirim) **cayma hakkından
  ayrıdır** ve daha uzun süreye tabidir. Sitede "14 gün geçti, hiçbir talebiniz geçerli
  değil" denemez.
- Garanti belgesi ve tanıtma-kullanma kılavuzu zorunluluğu olan ürün grupları için bunlar
  tüketiciye sağlanmalıdır.
- Kargoda hasar/kayıp riskinin kime ait olduğu ve tutanak süreci teslimat koşullarında yazılı olmalıdır.

---

## 8. Fatura ve belge düzeni

- İnternet üzerinden satış yapan mükellefler için e-Arşiv Fatura uygulaması esastır; ciro
  eşiklerini aşan mükellefler e-Fatura ve e-Defter uygulamalarına da geçer. Eşikler tebliğle
  güncellenir, güncel değerleri GİB'den teyit edin.
- İnternet üzerinden yapılan satışlarda faturaya **satışın internet üzerinden yapıldığına dair
  ibare** eklenir.
- Sevkiyatta faturanın veya irsaliyenin malın yanında bulunması gerekir.
- İade ve iptal işlemlerinde iade faturası / gider pusulası düzeni ayrıca kurgulanmalıdır.
- Fatura üzerindeki alıcı bilgileri ile sipariş kaydındaki bilgiler tutmalıdır; kurumsal
  fatura talebi alan sitelerde vergi dairesi ve vergi numarası alanları sipariş anında toplanır.

---

## 9. Ticari elektronik ileti ve İYS

Ticari elektronik ileti (SMS, e-posta, arama) göndermek için **önceden onay** gerekir ve
onaylar **İleti Yönetim Sistemi (İYS)** üzerinden yönetilir.

- Onay; alıcının kimliği, iletişim adresi, onay tarihi ve kanal bilgisiyle kaydedilir.
- Onayın alındığı ekran görüntüsü/kaydı ispat için saklanır.
- Her iletide **ret hakkı** kolay, ücretsiz ve açık şekilde sunulur.
- Ret talepleri gecikmeksizin işlenir ve İYS'ye yansıtılır.
- Sipariş bilgilendirmesi, kargo takibi gibi **işlem iletileri** pazarlama iletisi değildir;
  bunları pazarlama izniyle karıştırmak iki yönlü hataya yol açar (izinsiz pazarlama ya da
  ret verildiği için gönderilemeyen sipariş bildirimi).

Pazarlama izni, üyelik veya sipariş için **zorunlu koşul hâline getirilemez**.

---

## 10. Kişisel veri ve çerez

E-ticaret, kişisel verinin yoğun işlendiği bir alandır: ad, adres, telefon, sipariş geçmişi,
ödeme izleri, gezinme kayıtları.

- **Aydınlatma yükümlülüğü** her hâlde vardır; açık rıza yalnızca rızaya dayanan işlemeler için gerekir.
- Sözleşmenin ifası için zorunlu veriler rızaya bağlanmaz — aksi, rızayı geçersiz kılar.
- Veri saklama süreleri belirlenmeli ve süre dolduğunda silme/anonimleştirme gerçekten çalışmalıdır.
- Çerezlerde zorunlu olanlar dışındaki kategoriler için tercih ekranı sunulur; "siteyi
  kullanarak kabul etmiş sayılırsınız" yaklaşımı yeterli değildir.
- Yurt dışı kaynaklı analitik, reklam ve altyapı hizmetleri kullanılıyorsa aktarım rejimi
  ayrıca değerlendirilir.
- Veri ihlali hâlinde bildirim yükümlülüğü vardır; ihlal tespiti için loglama ve tespit
  mekanizması gerekir.

Detaylı bir başlangıç için: [kvkk-icin-web-gelistirici-rehberi](https://github.com/alestaweb/kvkk-icin-web-gelistirici-rehberi)

---

## 11. Fiyat gösterimi ve indirim

- Etikette/ürün sayfasında satış fiyatı ve varsa birim fiyat, tüm vergiler dâhil gösterilir.
- İndirimli satışta **indirimden önceki fiyat ile indirimli fiyat birlikte** gösterilir.
- "İndirimden önceki fiyat" yönetmelikte tanımlı bir referans döneme göre belirlenir. Bu
  dönemin uzunluğu değişikliğe uğradığı için, uygulamadan önce Fiyat Etiketi Yönetmeliği'nin
  yürürlükteki metnini kontrol edin.
- Bunun yazılım tarafındaki karşılığı net: **fiyat geçmişi tutmadan mevzuata uygun indirim
  gösterilemez.** Ürün fiyatını üzerine yazan bir tasarım, geçmişi imha ettiği için referans
  fiyatı hesaplayamaz.
- "Tükenmek üzere", "son 3 ürün", "kampanya bitiyor" gibi ifadeler gerçeğe uygun olmalıdır;
  gerçek olmayan aciliyet yaratma haksız ticari uygulama sayılır.

---

## 12. Uyuşmazlık: tüketici hakem heyeti

Tüketici uyuşmazlıklarında parasal sınırın altındaki başvurular tüketici hakem heyetlerine
yapılır. **2026 yılı için bu sınır 186.000 TL'dir** ve sınır her yıl yeniden değerleme
oranına göre güncellenir. Sınırın üzerindeki uyuşmazlıklar tüketici mahkemesinin görev alanındadır.

Satıcı tarafında pratik sonuç: hakem heyeti dosyaları büyük ölçüde **belge üzerinden**
karara bağlanır. Ön bilgilendirme onayı, sözleşme sürümü, kargo ve iade kayıtları düzgün
tutulmuşsa savunma kolay, tutulmamışsa savunma yoktur.

---

## 13. Yazılım tarafında ne anlama geliyor

Mevzuat maddelerinin bir **e-ticaret yazılımı** için karşılığı:

| Yükümlülük | Yazılımda karşılığı |
|---|---|
| Ön bilgilendirme ve sözleşme onayı | Her onay için ayrı kayıt: kim, ne zaman, hangi metin sürümü |
| Metinlerin sonradan değişmesi | Sözleşme metinlerinin sürümlenmesi, siparişin sürüme bağlanması |
| Kalıcı veri saklayıcısıyla iletme | Sipariş sonrası otomatik e-posta + gönderim kaydı |
| Cayma bildirimi | Bildirim formu, bildirim tarihinin ayrı alanda tutulması |
| İade süreci | İade durum makinesi: talep → onay → kargo → tahsil → geri ödeme |
| Fatura düzeni | e-Arşiv/e-Fatura entegrasyonu, internet satışı ibaresi, iade belgesi |
| İYS | İzin ve ret kayıtlarının çift yönlü senkronu, kanal bazlı izin |
| KVKK saklama süreleri | Zamanlanmış görevle silme/anonimleştirme, çalıştığının doğrulanması |
| İndirim gösterimi | Fiyat değişiklik geçmişi tablosu |
| İspat yükü | Kayıtların değiştirilemez şekilde ve yeterli süre saklanması |

Bir maddeyi yalnızca arayüzde çözmek (metni sayfaya koymak) çoğu zaman yetmez; hemen her
maddenin bir **kayıt** ayağı vardır. Denetimde ve uyuşmazlıkta sorulan şey ekran değil kayıttır.

---

## 14. Sık yapılan hatalar

| Hata | Sonucu |
|---|---|
| ETBİS kaydını "sonra yaparız" diye ertelemek | İdari yaptırım riski, doğrulama bandı gösterilemez |
| Aydınlatma metni ile açık rızayı tek kutuda birleştirmek | Rıza geçersiz sayılabilir |
| Onay kutularını önceden işaretli göndermek | Onay alınmamış sayılır |
| Ön bilgilendirme formu ile sözleşmeyi tek metin yapmak | İki ayrı yükümlülüğün biri karşılanmamış olur |
| Pazarlama iznini üyelik için zorunlu tutmak | İzin geçersiz, şikâyet konusu |
| Sözleşme metnini sürümlemeden güncellemek | Eski siparişlerde ispat sorunu |
| "İade kabul edilmez" gibi genel kayıtlar koymak | Geçersiz kayıt, tüketici lehine yorum |
| Fiyat geçmişi tutmadan indirim göstermek | İndirim gösterimi mevzuata aykırı kalabilir |
| Sipariş bildirimini pazarlama izniyle karıştırmak | Ya izinsiz ileti ya ulaşmayan sipariş bilgisi |
| Kargo ücretini son adımda sürpriz olarak eklemek | Toplam tutarın önceden bildirilmesi şartına aykırı |
| Saklama süresi tanımlayıp uygulamamak | Yazılı politika ile fiilî durum çelişir |
| Test siparişlerini gerçek kayıtların arasında bırakmak | Kayıt bütünlüğü ve raporlama sorunu |

---

## Makaleler

Rehberi tamamlayan, tek konuya odaklanan yazılar:

- [İnternetten satışta iade ve cayma hakkı: satıcıların sık yaptığı 12 hata](docs/iade-ve-cayma-hakki-12-hata.md)

---

## Kaynaklar

Yalnızca resmî kaynaklar:

- [Ticaret Bakanlığı — Tüketici Bilgi Sistemi](https://tuketici.ticaret.gov.tr/)
- [ETBİS — Elektronik Ticaret Bilgi Sistemi](https://www.eticaret.gov.tr/)
- [Mevzuat Bilgi Sistemi](https://www.mevzuat.gov.tr/) — 6502 sayılı Tüketicinin Korunması
  Hakkında Kanun, 6563 sayılı Elektronik Ticaret Kanunu, Mesafeli Sözleşmeler Yönetmeliği,
  Fiyat Etiketi Yönetmeliği
- [Kişisel Verileri Koruma Kurumu](https://www.kvkk.gov.tr/)
- [İleti Yönetim Sistemi](https://iys.org.tr/)
- [Gelir İdaresi Başkanlığı](https://www.gib.gov.tr/) — e-Fatura, e-Arşiv, e-Defter

---

## Katkı

Düzeltme ve ekleme için issue veya pull request açabilirsiniz. Kabul edilmeyenler:
belirli bir yazılım/hizmetin reklamı, ücret ve sözleşme bilgileri, kaynağı gösterilmemiş
hukuki yorum.

## Lisans

MIT

---

Bu rehber, haber ve e-ticaret platformları geliştiren [Alesta WEB](https://alestaweb.com/e-ticaret-yazilimi)
tarafından derlenmiştir.

Son güncelleme: 2026-10-12 (cayma hakkı bölümü 2026 değişikliklerine göre güncellendi)
