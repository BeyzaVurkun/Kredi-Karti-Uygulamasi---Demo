# Kredi Kartı Uygulaması - Demo

Bu proje, **HTML**, **CSS** ve **JavaScript** kullanılarak geliştirilmiş etkileşimli bir **kredi kartı demo uygulamasıdır**.  
Kullanıcı form alanlarını doldurdukça kart üzerindeki bilgiler anlık olarak güncellenir. **Gerçek bir ödeme işlemi yapılmaz**, tamamen demo ve UI/UX pratiği amaçlıdır.

## Özellikler

- **Kart numarası:** Form alanına girilen numara `.card-number-box` üzerinde anlık gösterilir. Mevcut uygulamada **maksimum 16 hane** kabul edilir.  
- **Kart sahibi ismi:** `.card-holder-name` alanına girilen metin **büyük harfle** görüntülenir.  
- **Geçerlilik süresi:** Ay ve yıl `select` (option) ile seçilir; yıl seçenekleri **2023–2033** aralığındadır ve kart üzerinde `AA / YY` formatında görünür.  
- **CVV & 3D dönüş:** CVV alanına odaklanıldığında kart arka yüzü `.back` ile görünür, çıkıldığında `.front` ön yüzüne döner.  
- **CVV girişi:** `.cvv-box` sadece **3 hane** kabul eder.  
- **Gönder butonu:** Formda demo amaçlı bir buton vardır; herhangi bir ödeme veya veri gönderimi yapmaz.

## Teknolojiler
- HTML5
- CSS3
- JavaScript

