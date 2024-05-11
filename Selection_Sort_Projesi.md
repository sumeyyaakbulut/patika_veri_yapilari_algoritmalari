# Selection-Insertion-Sort


#### Soru 1)
[22,27,16,2,18,6]  verilen dizinin insertion sort türüne göre aşamalarını yazınız.

#### Soru 1 Cevabı)
En baştan başlayarak dizinin en lüçük elamanı aranır. En küçüğü en başa alınır ve en başta olanla onun yeri değiştirlir. Bu şekilde her elamanı için bakılır.

```cadence
[22,27,16,2,18,6] --> n

[2,27,16,22,18,6] --> n-1

[2,6,16,22,18,27] --> n-2

[2,6,16,18,22,27] 
```

#### Soru 2)
[22,27,16,2,18,6] Big-O gösterimini yazınız.

#### Soru 2 Cevabı)
```cadence
n+(n-1)+(n-2)...1 = n.(n+1)/2 = n^2+n/2 => O(n^2)
```

#### Soru 3)
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1. Average case: Aradığımız sayının ortada olması
2. Worst case: Aradığımız sayının sonda olması
3. Best case: Aradığımız sayının dizinin en başında olması.

#### Soru 3 Cevabı)
Average case: Aradığımız sayının ortada olması
