# Insertion/Selection Sort

### Proje 1

> Q: [22, 27, 16, 2, 18, 6] -> Insertion Sort olarak verilen dizinin sort türüne göre aşamalarını yazınız.

> Q: Big-O gösterimini yazınız.
```
A: [22, 27, 16, 2, 18, 6] n
   [2, | 22, 27, 16, 18, 6] n-1
   [2, 6, | 22, 27, 16, 18] n-2
   [2, 6, 16, | 22, 27, 18] n-3
   [2, 6, 16, 18, | 22, 27] 1
------------------------------------
A: Big-O Notation: n*(n+1)/2
                   = O(n^2)
```

> Q: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
> - Average case: Aradığımız sayının ortada olması.
> - Worst case: Aradığımız sayının sonda olması.
> - Best case: Aradığımız sayının dizinin en başında olması.
```
A: Time Complexity: Dizi sıralandıktan sonra 18 sayısı ortada olduğu için cevap "Average Case"dir.
[2, 6, 16, 18, 22, 27]
```

> Q: [7, 3, 5, 8, 2, 9, 4, 15, 6] Dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
A: [2, | 3, 5, 8, 7, 9, 4, 15, 6]
   [2, 3, | 5, 8, 7, 9, 4, 15, 6]
   [2, 3, 4, | 8, 7, 9, 5, 15, 6]
   [2, 3, 4, 5, | 7, 9, 8, 15, 6]
   ---
   [2, 3, 4, 5, 6, | 9, 8, 15, 7]
   [2, 3, 4, 5, 6, 7, | 8, 15, 9]
   [2, 3, 4, 5, 6, 7, 8, | 15, 9]
   [2, 3, 4, 5, 6, 7, 8, 9, | 15]
```
