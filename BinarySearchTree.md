# Patika Veri Yapıları ve Algoritma Analizi Bölüm Sonu Projesi

## Binary Search Tree

**Başlangıç Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

**Kökü 7 kabul edelim.**

- Sıradaki eleman olan 5'i kök ile karşılaştıralım ve 5, 7'den küçük olduğu için sol alt ağaca ekleyelim.
- Sıradaki eleman olan 1'i kök ile karşılaştıralım ve 1, hem 7'den hem de 5'ten küçük olduğu için sol alt ağaca ekleyelim.
- Sıradaki eleman olan 8'i kök ile karşılaştıralım ve 8, 7'den büyük olduğu için sağ alt ağaca ekleyelim.
- Sıradaki eleman olan 3'ü kök ile karşılaştıralım ve 3, 7'den küçük olduğu için 5'in altında, 5'ten büyük olduğu için de 1'in yanına ekleyelim.
- Sıradaki eleman olan 6'yı kök ile karşılaştıralım ve 6, 7'den küçük ve 5'ten büyük olduğu için 3'ün sağ altına yazıyoruz.
- Sıradaki eleman 0'ı kök ile karşılaştırdığımızda 7'den küçük 5'ten küçük ve 1'den küçük olduğu için 0'ın altına yazıyoruz. 
- Sıradaki eleman 9'u kök ile karşulaştırdığımızda 7'den büyük ve 8'den büyük olduğu için 8'in sağ altına yazıyoruz. 
- Sıradaki eleman 4'ü kök ile karşılaştırdığımızda 7'den küçük, 3'ten büyük ve 6'dan küçük olduğu için 6'nın sol altına yazıyoruz.
- Sıradaki eleman 2'yi kök ile karşılaştırdığımızda 7'den küçük ve 3'ten küçük olduğu için 3'ün sol altına ekliyoruz.  



             7
            / \
           5   8
          / \   \
         1   3   9
        /   / \
       0   2   6
               /
              4
            


## Big O

- Time Complexity : Her elemanı ağaca eklemek için O(nlogn) zaman karmaşıklığına sahiptir.