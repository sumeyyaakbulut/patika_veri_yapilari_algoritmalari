# Merge Sort Projesi

#### Soru 1)
[16,21,11,8,12,22] dizinin merge sort türüne göre aşamalarını yazınız.

#### Soru 1 Cevabı)

```cadence
                                [16,21,11,8,12,22]
                           /                         \
1.Adım:               [16,21,11]                   [8,12,22]
                    /           \                 /          \
2.Adım:          [16,21]    -    [11]          [8,12]    -   [22]
                /        \          \         /      \           \
3.Adım:      [16]    -    [21]    -  [11]   [8]      [12] -  -  [22]   
                \       /              /      \       /         /
4.Adım:          [16,21]    -    [11]           [8,12]    -   [22]
                     \            /              \           /
5.Adım:                [11,16,21]                  [8,12,22]
                                  
6.Adım:                          [8,11,12,16,21,22]
```

#### Soru 2)
Big-O gösterimini yazınız.

#### Soru 2 Cevabı)

```cadence
Her bir adım O(n) , kaç defa O(n) yapılıyor dersek o zaman da 2^x = n  oda logn = x olur.
Bütün hepsini dahi edersek O(nlogn)

```
