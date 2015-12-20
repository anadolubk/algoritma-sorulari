# algoritma-sorulari
Programlamayı yeni öğrenen kişiler için kendilerini geliştirebilecekleri sorular

1. Çarpım tablosunu oluşturup ekrana yazacak programı yazınız.

Örnek çıktı: 
```
1x1 = 1
1x2 = 2
1x3 = 3
...
```

2. Aşağıdaki ekran çıktısını verecek programı yazınız.
```
*
**
***
****
```

3. Kullanıcıdan satır sayısını alarak satır sayısına göre aşağıdaki ekran çıktısını verecek programı yazınız.
```
    *
   ***
  *****
 *******
*********
 *******
  *****
   *** 
    *
```
	
4. Girilen bir string ifadede bulunan kelime sayısını ekrana yazan programı yazınız.

5. Girilen bi string ifadede bulunan harflerin kaç kere tekrar ettiğini ekrana yazan programı yazınız. Büyük ve küçük harfleri aynı karakter alın. Harf dışındaki karakterleri en sonra özel karakter olarak belirtin.

örnek çıktı:
```
a = 10
b = 7
c = 2
...
z = 3
ozel karakter = 19
```

6. 5\. soruda bulduğunuz sonuçları tüm harflere oranlayarak tekrar %'lerini bulunuz.

7. Kullanıcının klayeden girdiği boyuta göre bir dizi oluşturunuz. Bu diziye rastgele eleman atayınız. Diziyi ekrana yazdırınız. Diziyi aşağıdaki şekle getiriniz tekrar ekrana yazdırınız.
    
önceki hali: 1 7 94 3 95 43 2 4 55

sonraki hali: 1 55 7 4 94 43 95 3

(ilk eleman, sondan ilk eleman, 2. eleman sondan, 2. eleman ...)

8. Kullanıcıdan aldığınız 2 farklı en ve boy değerine göre 2 matris oluşturunuz. Bu matrislerin içini rastgele doldurup çarpmlarını ekrana yazdırınız.

9. Kullanıcının girdiği sayıyı asal çarpanlarına ayırıp ekrana yazınız.

10. Kullanıcının girdiği N'e göre bir NxN matris oluşturup simetrik olup olmadığını kontrol ediniz.

11. 3x3'lük bir matris tanımlayın. bu matrisin tüm elemanlarının 0 olduğunu garantileyin. ilk satırın rastgele bir hücresine 1 degeri girin. sonraki satırında yine aynı şekilde rastgele bir hücresine 1 degeri girin. ancak bu girdiğiniz değer daha önceki satırdaki hücreyle aynı sütun numarasına sahip olmasın. aynısını diğer satır için de uygulayın. matirsin son halini ekrana yazdırın. programı birden fazla kez çalıştırarak kontrol edin.

12. 11\. sorunda yapılanları 4x4, 6x6, 8x8 için tekrarlayın.

13. Aşağıdaki şekli döngüler kullanarak ekrana çizdirin.
```
|\|1|2|3|
|1| | | |
|2| | | |
|3| | | |
```

14. 11\. sorunun cevabını 13. soruda çizdiğiniz tablo üzerinde gösteriniz. 1 olan hücreler için * giriniz.

15. 13\. sorudakileri 12. soru için uygun hale getirip tekrarlayınız.

16. 5x5 boyutunda bir satranç tahtasında 5 vezir birbirini tehdit etmeden kaç farklı şekilde durabilirler. 15. soruya benzer şekilde çözünüz.

_Not:
4x4'lük bir satranç tahtasında 4 tane vezir birbirlerini tehdit etmeyecek şekilde 2 farklı şekilde durabilirler. Bunlar şu şekilde gösterilebilir._
```
|\|1|2|3|4|
|1| | |*| |
|2|*| | | | 
|3| | | |*|
|4| |*| | |

|\|1|2|3|4|
|1| |*| | |
|2| | | |*|
|3|*| | | |
|4| | |*| |
```

17. Normal bir satranç tahtasında 8 vezir birbirlerini tehdit etmeden kaç farklı şekilde durabilirler.

18. 1'den 100'e kadar olan sayıların toplamını ekrana yazdırın.

19. 1'den 100'e kadar olan sayılardan tek olanların karelerini, çift olanların yarılarını alarak bunları toplayın. sonucu ekrana yazın.

20. Kullanıcıdan aldığınız en ve boy'a göre bir dikdörtgen oluşturup bu dikdörtgenin alanını bulunuz.

21. 20\. soruda oluşturulan dikdörtgenin 2 eş parçaya bölündüğünü ve bölünen parçalardan birinin asıl dikdörtgenimiz olarak belirlendiğini düşünelim. Bu yaptığımız işlemin 10 kere yapılması sonucu elimizde kalan son dikdörtgenin alanını bulunuz.

_Not:
Bu işlemi her seferinde alanı 2'ye bölerek yapmayın. her seferinde dikdörtgenin alanını tekrar hesaplayın.
örnek olarak:_
```
en=4 boy=8 alan=32
en=4 boy=4 alan=16
en=4 boy=2 alan=8
en=4 boy=1 alan=4
en=4 boy=0.5 alan=2
en=4 boy=0.25 alan=1
en=4 boy=0.125 alan=0.5
en=4 boy=0.0625 alan=0.25
en=4 boy=0.03125 alan=0.125
en=4 boy=0.015625 alan=0.0625
en=4 boy=0.0078125 alan=0.03125
```

22. 21\. soruda sorulan işlemi kendinden bir büyük dikdörtgenin alanıyla kendi alanının farkı 0.0001 olana kadar tekrarlayın. Kullanıcının girdiği dikdörtgeni kaç kere parçaladığınızı ekrana yazdırınız.

23. 21\. soruda verilen örneğe baktığımızda dörtgeni her seferinde boydan 2'ye bölüp tekrar sonucu bulmuşuz. bunu yaptığımızda her seferinde dikdörtgenin üst parçasını bölmüş oluyoruz. 21. soruda yaptığımız işlemi dikdörtgenin alt kısımları için de tekrarlayalım.

_Not:
bu sorunun cevabını bulmak için recursive fonksiyon kullanmak doğru olacaktır._

24. 23\. soruda istenenleri 22\. soru için uyarlayınız.

25. y=x doğrusunun kullanıcıdan aldığınız başlangıç ve bitiş değerlerine göre integralini alınız.((x^2)/2 kullanılabilir)

_örnek olarak:_
```
baş:0 bit:8
sonuç 32
```

26. 23\. soruyu 25\. soru için uygun hale getirin. reimann toplamlarını hatırlamak işi kolaylaştırır. bu soruda (x^2)/2 gibi belirli bir çözüm kullanılmadan genel bir çözüm bulunmalı.