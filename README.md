# Binary Search Tree aşamaları

** Input: ** [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

## Aşamalar

1. Root sayı 7'dir.
2. 5, 7'den küçük, sol tarafa eklenir.
3. 1, 7'den ve 5'ten küçük, 5'in sol tarafına eklenir.
4. 8, 7'den büyük, 7'nin sağ tarafına eklenir.
5. 3, 7'den ve 5'ten küçük ve 1'den büyük, 1'in sağ tarafına eklenir.
6. 6, 7'den küçük ve 5'ten büyük, 5'in sağ tarafına eklenir.
7. 0, 1'in sol tarafına eklenir.
8. 9, 7 ve 8'den büyük, 8'in sağ tarafına eklenir.
9. 4, 7 ve 5'ten küçük, 1 ve 3'ten büyük, 3'ün sağ tarafına eklenir.
10. 2, 7 ve 5'ten küçük ve 1'den büyük, 3'ten küçük, 3'ün sol tarafına eklenir.

## Sonuç

```
          7
        /   \
       5     8
      / \     \
     1   6     9
    / \
   0   3
      / \
     2   4
```
