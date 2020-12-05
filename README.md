# hafta-3-4
Java Collection Framework, Java8 Features, Reflection, I/O Operations, MultiThreading


# Ödev Sorusu

**Açıklama1:** Soruların her biri ayrı ayrı algoritmaları ifade eder. Algoritma dediğimiz kavram bilgisayar programcılığı için çok önemli bir konudur.
Algoritma düşünce sistematiğini geliştirmeyen bir yazılımcı yazılım kütüphanelerini, programlama dillerini öğrenerek iyi bir programcı olma yolunda çok ileriye gidemez.

**Açıklama2:** Bu önemine istinaden ekstra algoritma ödevleriyle bu sizlerin bu yönünü geliştirmek hedefindeyiz.

**Açıklama3:** Verilen soruları Java dilinde kodlamanızı rica ediyorum. Ayrıca, hazır çözümler kullanmadan herkesin bireysel kodlamalasını rica ediyorum.
Yardımlaşma için birbirinizden ve benden yardım alabilirsiniz. Tek şart copy-paste kodlar lütfen olmasın :) Sizin gelişiminiz için bu çok önemlidir.

**Açıklama4:** Ödev sorularını yaparken takıldığınız yerlerde Google'da aramalar yaparak yardım alabilirsiniz. Unutmayın Google en büyük yardımcınız :)

#Sorular

**Soru1:** 
Çift yönlü LinkedList algoritmasını Generic sınıfları kullanarak kendiniz yazınız. (Java Collection Framework içindeki hazır LinkedList'i kullanmaMAnız gerekmektedir.)

**Soru2:** 
Book isminde bir sınıf tasarlayınız. Bu sınıf Comparable interface'den kalıtım alıp "compareTo" metodunu override ediniz. Bu metodun içinde kitabı A'dan Z'ye isme göre sıralayan kodu yazınız. Bu sınıftan 5 tane nesne oluşturun ve nesneleri Set tipinde bir yapısında saklayınız. Sonra ikinci kez Set tipinden bir veri yapısı kullanın ve kitapları sayfa sayısına göre sıralamasını sağlayınız.

Book sınıfı kitap ismi, sayfa sayısı, yazarın ismi, yayın tarihi değişkenlerinden oluşmaktadır.

**Soru3:** 
Kullanıcıdan öğrenci numarasını klavyeden girmesini sağlayın. Ardından öğrenciye ait isim, soyisim, yaş, bölüm bilgilerini klavyeden girin ve bu bilgileri Student sınıfında oluşturduğunuz nesnelerde saklayın. Öğrenci numarasına Student nesnesi tutulacak şekilde bir Map yapısında saklayınız.


**Soru4:** 
ArrayList ve LinkedList arasındaki farkları açıklayınız.


**Soru5:** 
a- Book sınıfından 10 tane nesne üretip bunu bir ArrayList yapısında saklayınız. stream yapısını ve lambda ifadelerini kullanarak kitap isminin karşısında yazar ismi olacak şekilde yeni bir Map<String, String> oluşturacak şekilde yazınız.

b- Bu 10 elemanlık Book listesinden sayfa sayısı 100'den fazla olan kitapları filtreleyen ve yeni bir liste olarak verecek geliştirmeyi yapınız. (Stream ve Lambda ifadeleri kullanabilirsiniz.)


**Soru6:** 
Öğrenciye ait öğrenci no, isim, soyisim, yaş, bölüm bilgilerini klavyeden okuyup dosyaya yazan bir program yazınız. Aynı programın içinde dosyayı okuyup tüm kayıtları ekrana yazan alt bir fonksiyon tasarlayınız.


**Soru7:** 
1'den 10000 (10 bin)'e kadar olan sayılardan oluşan bir ArrayList oluşturunuz. Ardından, bu ArrayList'teki 10 bin elemanı 2500 eleman olacak şekilde 4 eşit parçaya ayırınız. Bu 4 ayrı 2500 elemanlık ArrayList'ler içinde tek ve çift sayıları bulan 4 ayrı Thread tasarlayınız.

- 4 Thread bulduğu çift sayıları ortak bir ArrayList'e ekleyecektir.
- 4 Thread bulduğu tek sayıları ortak bir ArrayList'e ekleyecektir.
- Tek ve çift sayıları tutan ArrayList'ler ilk oluşturulduklarında boş olacaklardır. Ve iki tane ArrayList olacaklardır.
- 4 Thread kendine ait 2500 elemanlık ArrayList'i işlemeye başlayınca tek ve çift sayı ArrayList'lerini dolduracaktır.



**Bu bir sınav değildir! Geliştirmek için kodluyoruz ... :))**
