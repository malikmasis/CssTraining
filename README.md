# CssTraining
During learning CSS, notes which took from https://www.youtube.com/watch?v=yJsq0bqChko&list=PLadt0EaV4m3BX9JaZbKS9B8076bruv93Y&index=1&ab_channel=AdemIlter

TODO: Notlar üzerinden geçilerek düzeltilecektir.

css - adem ilter
ölçeklenebilir css

PostCSS 

--
tarayıcı developer editör seçimi

html yapısı inline ve block elementler

Seçiciler

cascading inheritance specifity
kutu model box-sizing
reset.css normalize.css

---
inline - b gibi
block - div ve p gibi - satırı komple kısıtlar
inline-block ,inline block özelliği kazandırır
initial: varsayılan özellik gösterir
inherit: kapsayıcı gibi davranır
none: gizlemek için - dom'da vardır
list-item: li özellikleri mevcut
table, table-row,table-cell
flex, inline-flex


styles: varsayılan değerler - sadece atanmışlar
computed: alınan bütün defaul özellikler

display:%30 css
user agent: tarayıcılardaki belirli farklıları vardır
normalize.css: bunları standart haline getirmek için

semantik etiketler: SEO - h1 başlık vs gibi konulara bakar.
css yazma yöntemleri
head içerisine <style>
<link rel="stylesheet" href:"site.css"/>

seçiciler - selectors
type selector - elementname
universal * 
class 
id
attribute []

Blog tasarlamak - yazı tipi ve özellikleri

Form Elemanları - 
bütün tipleri text bırakmamak lazım.
Telefonda açılırken ona uygun klavye açılıyor

input - düz isim
telefon - eposta
uzun satır - 
list 
radio button

button reset - defaultta olan özelliklere döndürür
submit -> action'daki url'e gönderir method -> default'ta get olur
https://httpbin.org/post gönder yaptığımızda bizi backend'e istek
atmışız gibi davranmamızı sağlr.
name="" önemli, çünkü arka tarafa bu vesileyle gönderir.

required- formu ilk zorunlu alanına focuslar

css sırasını da best practice olrak html'e göre
ayarlamak güzel olacaktır.

font-family kullanırken birden fazla kullanırken
sırayla bakarak ilk olanı uygular

padding-left: 15px - yön belirterek verir
padding: 15px  her 4 tarafa verir

inherit -> özelliği üst kapsayıcıdan al 

erişebilirik için tarayıcı her input için focus(outline) kullanır.

hex kodları aslında 6 hanelidir

.classname classname1 + classname1 {
    classname1'den sonra classname1 gelmesi durumunda uygulanır
}

classname > classname1{
    direkt altında classname1 bulunursa uygulanacak
}

button.primary{
    primary class'ı içeren butonlara uygulanır.
}
