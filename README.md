# 9Sinif-3 Ödev

Aşağıdaki yönerge adımlarını lütfen uygulayın. 

## Bölüm 1 (İvmeli Hareket Yapan Cismin Konum Zaman Grafiğinin Çizimi)

1) Bu ödevi kendi hesabınıza fork edin. Sonra da kendi hesabınızdan bu repoya ait Issue kısmını açın. (Ödevleriniz hakkında size yorum bırakabilmem için gerekli.) 

2) 2.ödevinizde doğrusal bir denklemin (1.dereceden) grafiğini hem elle hem de Google Sheet ile çizdiniz. Bu sefer ikinci dereceden bir denklemi Google Sheet ile çizeceksiniz. İkinci dereceden denkleminiz *y = ax^2+b*x+c* şeklinde olacak. Burada a,b, ve c katsayılardır. 
3) [Bu Videoyu](https://www.youtube.com/watch?v=--1-cfnicJ8) izleyin ve ikinci derecede denklemin nasıl Google Sheet ile çizileceğini öğrenin. Bu videoda bir karenin kenar uzunluğu ile alanın değişme grafiği çizilmiştir. Yani bu video için denkleminiz *y = x^2* şeklinde değişmiş. Yani *a=1, b=0,c=0* dır. 

4) [Bu Video'nun](https://www.youtube.com/watch?v=fhIL18aHg8s&feature=youtu.be) 1.kısmını izliyerek (11-26 saniye arası) 1 kg'lık bir kütlenin  zaman-konum grafiğini çizecekseniz. Burada ivmeli (yavaşlayan) bir hareket olacağından konum-zaman grafiği 2.dereceden denklem olarak çıkacak. 2.dereceden bir denklemi elle çizmeyi 10.sınıf matematik dersinde öğreneceksiniz. Siz bu ödevde bilgisayardan yardım alacaksanız. Video izliyerek çıkardığım zaman-konum tablosu aşağıdaki gibidir. (Not: Video 60 FPS(frame pers second) ile çekilmiştir. O zaman her frame(çerçeve) 1/60 s'dir. Siz istediğiniz noktayı orijin olarak alabilirsiniz. Ben 7'inci frameden başladım ve kütlenin sol ucunu başlangıç noktası seçtim. (x=0, t=0) 

| Frame | Zaman(s) | Konum (m)|
|-------|----------| ---------|
| 7 (Başlangıç)| 0 |   0      |
| 14    | 7/60     |   0.2    |
| 18    | 11/60    |   0.295  |
| 23    | 16/60    |   0.4    |
| 25    | 18/60    |   0.44   |
| 28    | 21/60    |   0.49   |
| 33    | 26/60    |   0.55   |
| 38    | 31/60    |   0.61   | 
| 45    | 38/60    |   0.65   |
| 48    | 41/60    |   0.67   |
| 53    | 46/60    |   0.675  |

Yukarıdaki aldığım verilerin Google Sheet'deki çizimini [burada](https://docs.google.com/spreadsheets/d/1PFojWqpQKHUI6shl7_bbvQSjrb3AS6kleerbCbNNWVg/edit?usp=sharing) bulabilirsiniz. Bu grafiği çizmek için, grafiğin üzerine iki kere tıkladım. Açılan yan pencerede aşağıdaki değişiklikleri yaptım. 
*   Chart Editor ------> Chart type -------> Scatter chart
*   Customize ------> Trendline -------> Polynomial,  Polynnomial Degree=2, Label= Use Equation

Bulduğum ikinci dereceden denklem (x= konum, t=zaman, *x= at^2+b*t + c*) şu şekilde çıktı:
*x = -1.22*t^2 + 1.81*t + 3.92E-03* 


Yukarıdaki örneği kullanarak **kendi ölçümlerinizle** bir tablo oluşturun (hiç değilse birkaç frame benim ölçümlerinden farklı olsun.) Kullandığınız Google Sheet için [buraya](https://docs.google.com/spreadsheets/d/1GaT3_0Ejzr-t0cHgo--S5K64pGeu7sP6jC57ypG-rzE/edit#gid=0) link verin (Google Sheet herkese açık erişimli olsun.) 

|Konum(m)|Zaman(s)|Frame|
|--------|--------|-----|
| 0      |   0    |  7    |
|0,09    | 0,05   |  10    |
|0,172   |    0,1 |   13   |
|0,24    |   0,15 |   16   |
|0,32    |   0,20 |   19   |
|0,39    |   0,25 |  22    |
|0,44    |  0,30  |    25  |
|0,49    |   0,35 |  28    |
|0,53    |  0,4   | 31     |
|0,57    |   0,45 | 34     |
|0,6     |    0,5 |   37   |
|0,63    |   0,55 |    40  |
|0,65    |  0,6   |  43    |
|0,66    |    0,65|  46    |
|0,67    |   0,7  | 49     |
|0,67     |  0,75 |  52    |
|0,67     |   0,8 | 55    |
|0,67     |  0,85 | 58     |
|0,67     |   0,9 |  61    |


a) Denkleminizi **x=-1,18t^2+1,78t+5,61E-03** Sizce a, b, ve c'nin fiziksel anlamları ne olabilir? Sizce niçin a'nın değeri negatif? 
a=ivme, b=ilk hız, c=konum. a negatiftir çünkü cisim zamanla yavaşlamaktadır.
b) Hava sürtünmesini ihmal edersek, bu harakette ivme sabit midir? Hayır, bu harekette olmaz çünkü ivmeyi ilgilendiren iki sürtünme var: Cisim ile zemin arasında ve cisim ile hava arasında. Hava sürtünmesini ihmal etsek dahi ivme sabit olmaz.
c) Video'daki cismin atılış hızı farklı olsaydı (diğer her şey aynı, kütle, yüzey, vb. Hava sürtünmesini ihmal edin), sizce formülde hangi terimler değişecekti? (a, b veya c) b değişirdi çünkü denklemde b ilk hızı ifade ediyor.

# Bölüm 2 (İvmeli Hareketin Ortalama Hız-Zaman Grafiği)
Bu sefer aynı cismin zaman-hız (ortalama hız) grafiğini çizeceksiniz. Bunun için *1.Bölümde* aldığımız sonuçları kullanacağız. Ortalama hızı bulmak için derste öğrendiğimiz ortalama hız formülünü (Delta x/ Delta t) kullanacağız. Google Sheet kullanarak hız-zaman grafiği nasıl çizildiğini anlamak için  [bu videoya](https://www.youtube.com/watch?v=67IsHRmcmfE&t) bakınız. Ortalama hız-zaman grafiğini çizilirken, ortalama hıza karşılık gelen zamanı nasıl belirleyeceksin? Bir andaki  ortalama hızı hesaplarken o noktadan önceki ve o noktadan sonraki (t,x) noktalarını kullanacaksın. Bu yüzden konum grafiğimde 11 veri noktam varken, hız-zaman grafiğinde veri noktam 9'a düştü. (İlk baştaki ve son baştaki noktalar için ortalama hızı hesaplayamam çünkü başlangıç noktasından önce ve bitiş noktasından sonraki (t,x) bilgilerine sahip değilim.)

Ben kendi verilerim için bir google sheet hazırladım. [Buraya](https://docs.google.com/spreadsheets/d/1fFw-F2NP9XpglTTEkqOjZETT7lD0iE9sqH3Da-srS9w/edit?usp=sharing) bakabilirsiniz. Ortalama hız grafiğini çizerken bu sefer 
*   Customize ------> Trendline -------> Linear, Label=Use Equation
kullandım. Konum-zaman grafiği 2.dereceden bir denklem iken, hız-zaman grafiği 1.dereceden (linear-doğrusal) denklem. 

1) Kendi aldığınız verileri kullanarak **ortalama hız-zaman** grafiğini Google çiziniz. [Buraya](https://docs.google.com/spreadsheets/d/1SO3pBT1TU9TZ4r8rRbtHtENr0X-c18va7SZgpJCIJYU/edit#gid=0) link veriniz.

2) Aynı Google Sheet'i kullanarak ivme verilerini Google Sheet'inize girin. (Bu sefer 7 tane ivme veriniz olacak.) İvme-zaman grafiğini çiziniz.

3) İvme'yi ne buldunuz? Bu ivme değerini kullanarak 1kg'lık cisim ile yüzey arasındaki kinetik sürtünme katsayısını bulunuz. 
İvme=-2,32. Kinetik sürtünme katsayısı=-16

# Bölüm 3 (Hala Beni Öldürmeyi Düşünmüyorsan)
1) Bu deneyde ölçüm hatalarım var. Zamandaki ölçüm hatam sizce kaç ms (mili saniye) nedir? Konumdaki ölçüm hatam sizce kaç cm'dir? 
Anladığım kadarıyla hata hesaplanırken ölçümün yarısı alınır. [Kaynak](https://www.mathsisfun.com/measure/error-measurement.html). Bu yüzden zamandaki ölçüm 0,766 ve yarısını alırsak 0,383 SANİYE hata payı olur. 0,383 saniye = 383 mili saniyedir. Konumdaki ölçüm ise 0,675 ve yarısı 0,3375 METREdir. 0,3375 metre= 33,75 santimetredir.
2) Acaba hiç grafik çizmeden sürtünme katsayısını bulabilir miydim?  (Cevap: Evet). 
Yardım:
* Düzgün ivmelenen bir cisim için alınan yol formülü x = (ilk hız+ son hız)/2*t, burdan cismin ilk hızını bulunuz. 
* Daha sonra iş-kinetik enerji teorimini kullanarak sürtünme kuvvetini bulun. Sürtünme kuvvetinden, kinetik sürtünme katsayısını bulunuz.

3) Bu video'dan statik sürtünme katsayısını bulabilir miydim? Bence hayır, cisim ilk başlarda hareketli olup yanlızca son anlarda yavaşlıyarak durmuştur.Elimizde yeterli bilgi yok. Belki tahminde bulunabilirdik ama ölçüm yapamazdık.
