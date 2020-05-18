Bu repoda zamaninda ARD ekibi ile yaptigim ve sayfamda yayinladigim PIC kontrollu Guc Kaynagi projesi bulunacak

https://www.barisdinc.com.tr/2011/06/15/0-25v-0-15a-ayarl-pic-gues-kaynag-boeluem-1/
https://www.barisdinc.com.tr/2011/04/08/0-25v-0-15a-ayarl-pic-gues-kaynag-boeluem-2/

Yaklaşık 1 yıl kadar önce, belki de çok daha önce, TA2FC Cengiz Abi’nin TA2NZ’ya bir hurda güç kaynağı hediye etmesi ile başladı herşey. Daha sonra dernekte (ARD-Amatör Radyocular Derneği) TA2GY Cem’in bu  PIC tabanlı şemanın kartını çizmeye çalışması ile ilerledi. Ben neresinde nasıl dahil oldum hatırlamıyorum ama bir şekilde içine girerek yeni özellikleri yazılıma ekledim.

Bu yeni özellikler şunlardı :

1) Voltaj-Akım arttırıp azaltmak için var olan 8-10 butonu kaldırıp bunun yerine bir rotary encode kullanmak

2) Rotary Encoderin çevrilme hızına göre artış/azlış hızının değişmesi

3) Voltaj-Akım ayar adımlarının ayarlanabileceği bir ayar menüsünün olması

4) Pil tipne öre (NiCD, LiOn, voltaj, akım, adet, vb.) şarj yapabilen bir pil şarj yazılımı

5) LCD göstergede bir takım güncellemeler

6) Okunan değerin hızlı değişimleirnin yumuşatılması (ortalamalar alarak değerin sürekli değişmesini engellemek)

vesaire… vesaire…




Bu arada TA2NZ Şahin hurdalıkta çok sayıda toroid trafo ve uygun kondansatör bulup dernekteki pek çok arkadaşa dağıtmı, TA2GY Cem uygun bir kutu tespit ederek soğutucu,LCD gibi malzemelerin toplu siparişini vermişti. İş başa düşmüştü artık, arkadaşların yoğun baskıları ile (sağolsunlar direk baskı uygulamadılar ama ben kendi kendimi bir baskı altında hissetmiyordum desem yalan olur) ilk sürümlerini tamamladık.. Önce TA2OU Mesut’un cihazını kobay kullanıp ayağa kaldırdık, sonra TA2UZ Hayrettin, sonra TB2CQP Şerif sonra TA2GV Veysel…

Ben kendime yaptığım güç kaynağını arkadaşlarınki kadar güzel bir kutuya koyamadım ama çok da kötü sayılmaz 🙂

Bu yazıda 7 yazı dizisinde sizlerle hem şemayı, hem baskı devreyi hem de PICBASIC ile yazılmış kodları paylaşacağım. Pek PICBASIC konusunda başarılı olmasamda herkesin anlayıp değişiklik yapabilmesi için bu projeyi PICBASIC şle yazmanın çok daha iyi olacağını böylece uygulayan sayısının çok daha fazla olacağını düşünüyorum.

Yazılarımda cihazın nasıl çalıştığı ile ilgili detay bilgiler ve çalışma prensibi konusundaki bilgilerimi, ilk çalıştırıldığında nasıl test edileceğni filan da anlatmayı planlıyorum.

NOT : Bu devrenin orjinali VE2EMM cağrı işaretli Kanadalı bir amatör telsizci tarafından yapılmış. Devrenin birkaç hatası var bu konuda dikkatli olunması gerekiyor, aslında biz hızlı başladığımız için bu olumsuz yönlerin ilk başta farkedemedik, farketmiş olsaydık başka bir çözüme geçerdik. Bu olumsuzlukların nasıl ve ne derece giderdiğimizi yazının ileleyen bölümlerinde anlatacağım.

Önce biraz reklam olsun diye fotoğraf ve video koyarak başlamak istiyorum:

              
