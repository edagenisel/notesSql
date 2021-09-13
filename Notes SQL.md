

Veritabanında yatan verileri istediğimiz şekilde filtreleyip işlem yapabilmemiz için sql yardımcı

olabilir.

Normalizasyon→tekrarlanmış veriden kurtularak sunucuyu hızlandırmak, veriler arası tutarlılığı

sağlamak için yapılan işlem.

**Veri Tipleri**

Char, nchar, varchar,text, binary, image, bit, int, decimal,money, date, datetimeoffset,date,

smalldate

**Komutlar**

Select\*from … : tabloda istenen veriyi alır

Create: Bir veritabanı veya veritabanı içinde tablo oluşturur, ya da database olusturmak icin

Insert into: boş bir tablo içinde oluşturduğumuz sütunlara very eklemek.

Update: bir tablo içerisindeki kayıtların değiştirilmesi, güncellenmesi için

Delete: Veritabanındaki verileri siler.

Truncate: veriyi özellikleriyle birlikte ortadan kaldırır.

Alter: Veritabanın nesnesinin yapısını dğeiştirmek için

Where: şart belirtmek icin kullanılır

And: tüm koşulları sağlamalı

Or: en az 1 koşulu sağlamalı

Distinct: exceldeki yenilenenleri kaldırır

Order by: sıralama için kullanılır

-asc (artan sıralama)

-desc(Z’den A’ya sıralama)

In/not in: belirli verileri getirmek veya getirmemek için çok sık kullanılır.

Top: belirli bir sayıda veriyi çekmek için kullanılır.

select top n\*from ilgili tablo adı

Select top n percent\*from tablo adı(ilgili tablo içinde %nlik veriyi getirir)

Select count: toplam bulmak icin kullanılır.

Select avg/min/max: ortalama max min dğeerler için kullanılır.

Select getdate(): Hangi tarih ve saatte bulunuyorsann o veri gelir.

Dateport: herhangi bir tarihi parçalamak için , içerisinde herhangi bir tarih parametresi varsa bunu

bizim istediğimiz şekilde bölüyor.

Datediff: seçilen iki tarih arasındaki farkı gösterir.

Datename: istenilen tarihsel veriyi metinsel halinde gösterir.

Dateadd: bugünden n zaman sonraki tarihi verir.





Upper: istenilen veriyi büyük harf yapar

Len: isimlerin uzunluğunun kaç harf olduğunu öğrenmek için

Substring: bir tablodaki seçilen verinin kaçıncı harfinden başlayarak hangi harfine kadar gösterilmek

isteniyorsa onu getirir.

Reverse: tersten yazma

Concat: verileri birleştirir.

Replicate: Bir karakteri istediğimiz kadar yazar.

Having: gruplama yaparken şartlı sorgu.


