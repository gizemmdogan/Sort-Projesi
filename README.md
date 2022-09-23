# Sort Projeleri
Kodluyoruz eğitim projesi 

## Insertion Sort
Insertion Sort Projesi
### Soru 1
[22,27,16,2,18,6] -> Insertion Sort

* [22,27,16,2,18,6]
* [2,27,16,22,18,6]
* [2,6,16,22,18,27]
* [2,6,16,18,22,27]
 
 O(n^2)

- Average case: n^2
- Worst case: n^2
- Best case: n

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. Average case

### Soru 2

 [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

 * [7,3,5,8,2,9,4,15,6]
 * [2,3,5,8,7,9,4,15,6]
 * [2,3,4,8,7,9,5,15,6]
 * [2,3,4,5,7,9,8,15,6]
 * [2,3,4,5,6,9,8,15,7]
---

 ## Merge Sort
Merge Sort Projesi

### Soru 

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

* O(nlogn)

* [16,21,11,8,12,22]
* [16,21,11] [8,12,22]
* [16,21] [11] [8,12] [22]
* [16] [21] [11] [8] [12] [22]
* [16] [11,21] [8] [12,22]
* [11,16,21] [8,12,22]
* [8,11,12,16,21,22]

## Binary-Search-Tree Sort
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```
          [5]
       /       \ 
    [1]         [7]
   /   \        /  \
[0]    [3]     [6]  [8]
       / \             \
    [2] [4]              [9]
    
```
Root 5