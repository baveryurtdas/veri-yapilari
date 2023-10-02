# Patika Veri Yapıları ve Algoritma Bölüm Sonu Projesi

## Insertion Sort

**Dizi : [22, 27, 16, 2, 18, 6]** 

1. [22, 27, 16, 2, 18, 6]
2. [22, 27, 16, 2, 18, 6]
3. [16, 22, 27, 2, 18, 6]
4. [2, 16, 22, 27, 18, 6]
5. [2, 16, 18, 22, 27, 6]
6. [2, 6, 16, 18, 22, 27]

**Insertion Sort'un zaman karmaşıklığı (time complexity) dizi uzunluğuna (n) bağlı olarak değişir :**


- Best case: O(n) - Dizi sıralı olduğunda, her eleman sadece bir kere karşılaştırılır ve yer değiştirilir.

- Avarage Case: O(n^2) - Ortalama durumda, her elemanın sıralı kısmın içinde uygun konuma yerleştirilmesi gerekebilir.

- Worst case: O(n^2) - Dizi tersten sıralı olduğunda, her elemanın sıralı kısmın sonuna yerleştirilmesi gerekebilir.

**Bu durumda, dizi sıralandıktan sonra 18 sayısı için :**


- Average case: Aradığımız sayının ortada olması, Insertion Sort'un ortalamada O(n^2) olduğu göz önüne alındığında ortalamada bulma süresi beklenenden daha uzun sürebilir. 

- Worst case: Aradığımız sayının sonda olması, Insertion Sort'un en kötü durumda O(n^2) olduğu için en kötü senaryoda da uzun sürebilir.

- Best case: Aradığımız sayının dizinin en başında olması, Insertion Sort'ta O(n) kadar hızlı bulmanızı sağlar. Ancak bu sadece en iyi senaryo için geçerlidir ve genellikle bu şekilde gerçekleşmez.

**Sonuç olarak, 18 sayısının sıralandıktan sonra aranma süresi genellikle O(n^2) olan Insertion Sort için average veya worst case senaryolarına daha yakın olacaktır.**

--- 

**Dizi : [7,3,5,8,2,9,4,15,6]** 

**Adım 1 : Minimum elemanı bul ve ilk elemanla değiştir.**

- Minimum eleman : 2 (index 4)
- [2, 3, 5, 8, 7, 9, 4, 15, 6]

**Adım 2 : Minimum elemanı bul ve ikinci elemanla değiştir.**
- Minimum eleman: 3 (index 1)
- [2, 3, 5, 8, 7, 9, 4, 15, 6]

**Adım 3 : Minimum elemanı bul ve üçüncü elemanla değiştir.**
- Minimum eleman: 4 (index 6)
- [2, 3, 4, 8, 7, 9, 5, 15, 6]

**Adım 4 : Minimum elemanı bul ve dördüncü elemanla değiştir.**
- Minimum eleman: 5 (index 6)
- [2, 3, 4, 5, 7, 9, 8, 15, 6]