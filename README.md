# Proje 1 Insertion Sort Porjesi

## Insertion Sort Aşamaları

```
 [22,27,16,2,18,6]
 [16,22,27,2,18,6]
 [2,16,22,27,18,6]
 [2,16,18,22,27,6]
 [2,6,16,18,22,27]
```

## Big O Notation Gösterimi
```
Worst Case: O(n^2)
Avarage Case: O(n^2)
Best Case: O(n)
```

## Time Complexity
```
Best Case: [2,6,16,18,22,27]
Worst Case: [27,22,18,16,6,2]
```
## 18 Sayısının Case Durumu
```
Avarage Case
```
## [7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı
```
[7,3,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
```

# Merge Sort Projesi

## Aşamalar
```
[16,21,11,8,12,22] ikiye bölünür
- [16,21,11]     [8,12,22]
Tekrar ikiye bölünür
- [16,21]   [11]   [8,12]   [22]
2 veya daha az elemanda bölme işlemi durdurulur
Diziler kendi içinde sıralanır
- [16,21]   [11]   [8,12]   [22]
Elde olan diziler uygun şekilde birleştirilir
- [11,16,21]   [8,12,22]
Birleştirme işlemi devam eder
- [8,11,12,16,21,22]
Son hal elde edilmiş olur
```

## Big O Notation Gösterimi
```
Worst case: O(n*logn)
Average case: O(n*logn)
Best case: O(n*logn)
```

# Binary Search Tree Projesi

## Aşamalar
```
7
```

```
  7
 /
5
```
```
    7
   /
  5
 /
1 
```
```
    7
   / \
  5   8
 /
1 
```
```
    7
   / \
  5   8
 / 
1  
 \
  3
  ```
  ```
      7
   / \
  5   8
 / \
1   6
 \
  3
  ```
  ```
        7
     / \
    5   8
   / \
  1   6
 / \
0   3
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
```
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
  ```
  
