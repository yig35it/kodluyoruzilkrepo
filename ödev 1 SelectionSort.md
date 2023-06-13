># SelectionShort ödevi cevabı 

#[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.Average case: Aradığımız sayının ortada olması
2.Worst case: Aradığımız sayının sonda olması
3.Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
[22, 27, 16, 2, 18, 6] (Başlangıç durumu)
[22, 27, 16, 2, 18, 6] (27, 22'den büyük olduğu için yer değiştirme yapılmaz)
[16, 22, 27, 2, 18, 6] (16, 27'den küçük olduğu için yer değiştirme yapılır)
[2, 16, 22, 27, 18, 6] (2, 22'den küçük olduğu için yer değiştirme yapılır)
[2, 16, 18, 22, 27, 6] (18, 27'den küçük olduğu için yer değiştirme yapılır)
[2, 6, 16, 18, 22, 27] (6, 22'den küçük olduğu için yer değiştirme yapılır)
Big-O gösterimi: O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı en iyi durumu olan Best case'e girer. Çünkü aradığımız sayı dizinin en başında bulunuyor.

[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort aşamaları:

[2, 3, 5, 8, 7, 9, 4, 15, 6] (2, en küçük eleman olduğu için yer değiştirme yapılır)
[2, 3, 5, 8, 7, 9, 4, 15, 6] (3, en küçük eleman olduğu için yer değiştirme yapılmaz)
[2, 3, 4, 8, 7, 9, 5, 15, 6] (4, en küçük eleman olduğu için yer değiştirme yapılır)
[2, 3, 4, 5, 7, 9, 8, 15, 6] (5, en küçük eleman olduğu için yer değiştirme yapılır)
İlk 4 adım bu şekildedir.
````
