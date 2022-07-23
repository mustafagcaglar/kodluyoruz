# 1)

- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

-               7
               / \
              5   8
             / \   \
            1   6   9
           / \
          0   3 
             / \
            2   4 
- Rootu 7 olarak belirlediğimizde binary search tree yöntemine göre sayının sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar bulunmalıdır. Bu yüzden öncelikli olarak 7nin soluna 5 sağına 8 yazarız. 5'ten devam edersek 5'in solunda 1 sağına 6 yazarız. 7'den küçük 6'dan büyük bir sayı kalmadığı için sağ tarafı sonlandırıyoruz. Solda 1'in soluna 0 sağına 3 yazarız. Solda 0'dan küçük bir sayı kalmadığı sol tarafı sonlandırıyoruz. 3'ün soluna 2 sağına 4 yazarız ve 7'den küçük farklı bir eleman kalmadığı için 7'nin sol tarafını sonlandırıyoruz. 7'nin sağına 8 sayısını yazıyoruz. 8'in soluna yazabileceğimiz 7'den büyük 8'den küçük bir sayı olmadığı için 8'in solunu sonlandırıyoruz. 8'in sağına 9 yazıyoruz. 7'den büyük farklı bir eleman kalmadığı için 7'nin sağ tarafını sonlandırıyoruz ve binary search tree aşamalarımız bitiyor.
