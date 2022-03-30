# MergeSortProject

Bu repo [Patika](https://app.patika.dev/paths) eğitimi kapsamında açtığım repo.

## [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

* Aşamalar:

```text

    [16, 21, 11, 8, 12, 22]
        /             \
  [16, 21, 11]     [8, 12, 22]
      /   \           /   \
  [16, 21] [11]   [8, 12] [22]
    /  \     |      /  \    |
 [16] [21]  [11]  [8] [12] [22]
   \    /    |     \   /    |
  [16, 21]  [11]  [8, 12]  [22]
     \       /       \      /    
   [11, 16, 21]    [8, 12, 22]
         \             /
      [8, 11, 12, 16, 21, 22 ]
```

Big-O gösterimini yazınız.

```text
O(nlogn)
```
