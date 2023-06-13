# MergeSort Ödevi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

# CEVAP
```
Başlangıç dizisi: [16, 21, 11, 8, 12, 22]
Diziyi ikiye bölerek alt dizilere ayırma: [16, 21, 11] ve [8, 12, 22]
Her alt diziyi aynı yöntemle daha küçük alt dizilere bölmeye devam etme:[16], [21, 11] ve [8], [12, 22]
Her alt diziyi sıralama:[16], [11, 21] ve [8], [12, 22]
İki alt diziyi birleştirerek daha büyük alt diziler oluşturma:[11, 16, 21] ve [8, 12, 22]
on olarak, iki büyük alt diziyi birleştirerek tam sıralanmış bir dizi oluşturma:[8, 11, 12, 16, 21, 22]

Merge Sort'un Big-O gösterimi, en kötü durumda O(n log n) şeklindedir. Bu, Merge Sort'un n elemanlı bir diziyi sıralamak için ortalama olarak n log n adım gerektirdiği anlamına gelir.
```