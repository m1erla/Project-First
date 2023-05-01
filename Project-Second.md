# [16,21,11,8,12,22] -> Merge Sort

## 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[16,21,11,8,12,22]

 splits in two -- [16,21,11] [8,12,22]

[16,21] [11] [8,12] [22]

Left until only one member remained. It will be merged in order. --[16] [21] [11] [8] [12] [22]

[16,21] [11] [8,12] [22]

[11,16,21] [8,12,22]

[8,11,12,16,21,22]

## 2) Big-O gösterimini yazınız.

O(nlogn)
