# Merge Sort
[16,21,11,8,12,22]
## Merge Sort Adımları
- [16,21,11,8,12,22]
- [16,21,11] [8,12,22]
- [16,21] [11] [8,12] [22]
- [16] [21] [11] [8] [12] [22]
- [16,21] [11] [8,12] [22]
- [11,16,21] [8,12,22]
- [8,11,12,16,21,22]
## Big-o Notation 
Her adımda (n-1) işlem yapıyorum. Time complexityde baskın olanı aldığımız için O(n)
2^x= n
x= logn
Merge Sort= O(nlogn)