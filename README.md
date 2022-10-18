# Veri-Yapilari-Ve-Algoritmalar-2
## patika.dev - Merge Sort Projesi

## Proje 2
[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

## Sort türüne göre aşamaları
   ```
   [16,21,11,8,12,22]
[16,21,11]   |  [8,12,22]
[16,21]   [11] | [8,12]   [22]
[11,16,21] | [8,12,22]
[8,11,12,16,21,22]
```

## Big-O gösterimi
```
Diziyi çözümlemede her seferinde yarıya indirdiğimiz için 2^x=n'dir. Ve çözümü logn = x bulunur 
Dizilim için n-1 sorgulama yapılır ve time complexity O(n) olur.
Birlikte çözümlenirse Big O notation tüm caseler için O(n*logn)'e eşit olur.
```
```
Worst case   : O(n*logn)
Average case : O(n*logn)
Best case    : O(n*logn)
```    
www.patika.dev
