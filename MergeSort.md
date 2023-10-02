# Patika Veri Yapıları ve Algoritma Analizi Bölüm Sonu Projesi

## Merge Sort

**Dizi : [16,21,11,8,12,22]**

1. Dizi ikiye böleriz **(Divide)** Sol Yarım: **[16,21,11]** ve Sağ Yarım: **[8,12,22]**
2. Fethetme **(Conquer)** : Her iki yarıyı ayrı ayrı sıralarız. Bu her iki yarının da kendi içinde sıralanmış bir hale gelmesi demektir. Bu adımı tekrar tekrar yaparız. 
    - Sol Yarıyı Bölme ve Sıralama : 
        - **[16,21,11] -> [11,16,21]**
    - Sağ Yarıyı Bölme ve Sıralama : 
        - **[8,12,22] -> [8,12,22]**

3. Birleştirme **(Merge)** : Sıralanmış iki yarıyı birleştirerek orjinal diziyi sıralarız.
    - **[8,11,12,16,21,22]**

## Big O 

- Merge Sort O(n log n) zaman karmaşıklığına sahiptir ve genellikle büyük veri setlerini sıralamak için etkili bir sıralama algoritmasıdır.
