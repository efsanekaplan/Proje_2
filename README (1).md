# Global-AI-Hub-Project-2

 
## Projede istenenler

* Veri setine göre uzun soluklu filmler hangi dilde oluşturulmuştur? Görselleştirme yapınız.
* 2019 Ocak ile 2020 Haziran tarihleri arasında 'Documentary' türünde çekilmiş filmlerin IMDB değerlerini bulup görselleştiriniz.
* İngilizce çekilen filmler içerisinde hangi tür en yüksek IMDB puanına sahiptir?
* 'Hindi' Dilinde çekilmiş olan filmlerin ortalama 'runtime' suresi nedir?
* 'Genre' Sütunu kaç kategoriye sahiptir ve bu kategoriler nelerdir? Görselleştirerek ifade ediniz.
* Veri setinde bulunan filmlerde en çok kullanılan 3 dili bulunuz.
* IMDB puanı en yüksek olan ilk 10 film hangileridir?
* IMDB puanı ile 'Runtime' arasında nasıl bir korelasyon vardır? İnceleyip görselleştiriniz.
* IMDB Puanı en yüksek olan ilk 10 'Genre' hangileridir? Görselleştiriniz.
* Runtime' değeri en yüksek olan ilk 10 film hangileridir? Görselleştiriniz.
* Hangi yılda en fazla film yayımlanmıştır? Görselleştiriniz.
* Hangi dilde yayımlanan filmler en düşük ortalama IMBD puanına sahiptir? Görselleştiriniz.
* Hangi yılın toplam "runtime" süresi en fazladır?
* Her bir dilin en fazla kullanıldığı "Genre" nedir?
* Veri setinde outlier veri var mıdır? Açıklayınız.


## Proje içindeki dosyalar
* proje 2




##  Uygulamanın akışı

NetflixOriginals.csv dosyası oyundu ve df dataframe sine çevrildi
df.head() ve df.info() ile ilk beş değer alındı ekrana basıldı.

![image](https://user-images.githubusercontent.com/93267352/180611136-ee119733-96a5-4efe-95b5-e8ca95180bee.png)

1. Veri setine göre uzun soluklu filmler hangi dilde oluşturulmuştur? Görselleştirme yapınız.
seaborn kütüphanesi yardımıyla istenen değerler filtrelendi.

2. İngilizce çekilen filmler içerisinde hangi tür en yüksek IMDB puanına sahiptir?

Dataframe içerisinden dili ingilizce olan filmlerin imdb sıralaması büyükten küçüğe alında ve ilk değer türü alındı.

3. 'Hindi' Dilinde çekilmiş olan filmlerin ortalama 'runtime' suresi nedir?

Dataframe içerisinden dili hintçe olan filmlerin sürelerinin ortalaması

4. "Genre" Sütunu kaç kategoriye sahiptir?

Dataframe içerisinden genre'ların value_counts() bulundu ve uzunlukları bastırıldı.

5. "Genre" Sütunundaki kategoriler nelerdir?
Dataframeden genre sütunu çekildi ve unique/eşsiz değerleri filtreledik.
Bastırdırıldı.

6. Veri setinde bulunan filmlerde en çok kullanılan 3 dil nedir?

Dataframeden language sütunlarından  3 değer çekildi ve sayılarını
bastırdırıldı.

7. IMDB puanı en yüksek olan ilk 10 film hangileridir?

Imdb puanı en yüksek ilk 10 filmin isimleri yazdırıldı.

8. IMDB puanı ile 'Runtime' arasında nasıl bir korelasyon vardır? Görselleştiriniz.

IMDB puanı ve Runtime arasındaki korelasyonu bulmak için grafik çizilde ama hiçbir korelasyon bulunamadı.

9. IMDB Puanı en yüksek olan ilk 10 'Genre' hangileridir? Görselleştiriniz.

IMDB Puanı en yüksek olan ilk 10 'Genre' nın scatter grafiği çizildi.

10. 'Runtime' değeri en yüksek olan ilk 10 film hangileridir? Görselleştiriniz.

Süresi en yüksek olan filmin çizgi grafiği çizdirildi.

11. Hangi yılda en fazla film yayınlanmıştır? Görselleştiriniz.

Dataframe'den Premiere değerlerinin value_count() 'ının ilk değeri alındı.

12. Yıllara göre yayınlanan film sayıları nelerdir? Görselleştiriniz.

Yıllara göre yayınlanan film sayıları barh grafiği ile gösterildi.

13. Hangi dilde yayınlanan filmler en düşük ortalama IMBD puanına sahiptir? Görselleştiriniz.

En düşük 50 IMDB Score sahiplerin yılları gösterilip scatter grafikle görselleştirildi.

14. Hangi yılın toplam "runtime" süresi en fazladır?

Toplam runtime süresi en fazla olan yıl yazdırıldı.

15. Her bir dilin en fazla kullandığı "Genre" nedir?

Her bir dilin en fazla kullandığı "Genre" ve her bir dilin en fazla kullanıldığı "Genre" yazdırıldı.

16. 2019 Ocak ile 2020 Haziran tarihleri arasında 'Documentary' türünde çekilmiş filmlerin IMDB değerlerini bulup görselleştiriniz.

Premiere'deki obje tipindeki veriyi datetime a çevrildi.
istenilen tarihler arasındaki veriler filtrelendi.

17. Veri setinde outlier veri var mıdır?

Veri setindeki outlier verileri görmek için boxplot ve histogram kullanıldı.
Çeyrekler açıklağı ile outlier veri sayısı bulundu.
Burda outlier veri olduğu gözlemlendi.

## Kullanılan paketler/Kütüphaneler

* Pandas
* Numpy 
* matplotlib
* seaborn 
* datetime

## Kullanılan kaynaklar
* https://globalaihub.com/courses/introduction-to-python/
* https://globalaihub.com/courses/introduction-to-python-the-road-to-machine-learning/
* [StackOverFlow](https://stackoverflow.com/)
* https://www.geeksforgeeks.org/python-programming-language/?ref=lbp
* (https://docs.python.org/3)
* https://pandas.pydata.org/
* https://ravenfo.com/
* https://www.kaggle.com/learn
* https://medium.com/bili%C5%9Fim-hareketi/veri-bilimi-i%CC%87%C3%A7in-temel-python-k%C3%BCt%C3%BCphaneleri-2-pandas-dcc12ae01b7d




