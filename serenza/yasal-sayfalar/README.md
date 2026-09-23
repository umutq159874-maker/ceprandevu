# Serenza – Yasal Sayfalar

Shopify mağazası için hazır metin şablonları. Köşeli parantez içindeki alanları
kendi bilgilerinle doldur, sonra Shopify'a yapıştır.

> ⚠️ Bunlar genel şablonlardır, hukuki danışmanlık değildir. Satışlar başladığında
> bir avukata veya mali müşavire kısaca göz attırman iyi olur.

## Doldurman gereken alanlar

| Alan | Örnek |
|---|---|
| `[SATICI ADI SOYADI / UNVANI]` | Umut ... (şirket kurulunca şirket unvanı) |
| `[ADRES]` | Tebligat adresin |
| `[TELEFON]` | 05xx xxx xx xx |
| `[E-POSTA]` | destek@alanadin.com |
| `[VERGİ DAİRESİ / VERGİ NO veya TCKN]` | Şirket yoksa TC kimlik no |
| `[ALAN ADI]` | serenza.com.tr (senin domainin) |
| `[KARGO FİRMASI]` | Tedarikçinin çalıştığı kargo firması |
| `[TESLİMAT SÜRESİ]` | Örn. 1–5 iş günü (tedarikçine sor) |
| `[İADE ADRESİ]` | Tedarikçinin iade deposu veya kendi adresin |

## Dosyalar ve Shopify'da nereye konacağı

| Dosya | Shopify'da yeri |
|---|---|
| `mesafeli-satis-sozlesmesi.md` | Ayarlar → Politikalar → **Hizmet Şartları** |
| `on-bilgilendirme-formu.md` | Online Mağaza → Sayfalar → Yeni sayfa |
| `iade-ve-cayma-hakki.md` | Ayarlar → Politikalar → **Geri Ödeme Politikası** |
| `kvkk-aydinlatma-metni.md` | Online Mağaza → Sayfalar → Yeni sayfa |
| `gizlilik-ve-cerez-politikasi.md` | Ayarlar → Politikalar → **Gizlilik Politikası** |
| `kargo-ve-teslimat.md` | Ayarlar → Politikalar → **Kargo Politikası** |
| `iletisim.md` | Online Mağaza → Sayfalar → Yeni sayfa |

Sayfaları oluşturduktan sonra: **Online Mağaza → Gezinme → Footer menüsü**'ne
hepsini ekle. PayTR onayı için bu sayfaların sitede görünür olması gerekir.

## Ödeme sayfası (checkout) ayarı

Ayarlar → Ödeme (Checkout) bölümünde müşterinin sipariş vermeden önce
Ön Bilgilendirme Formu ve Mesafeli Satış Sözleşmesi'ni okuduğunu onaylaması
gerekir. Shopify'da bunun için "şartları kabul et" onay kutusu ekleyen bir
uygulama (App Store'da "terms and conditions checkbox" diye aratabilirsin)
veya temanın sepet sayfasındaki onay kutusu kullanılabilir.
