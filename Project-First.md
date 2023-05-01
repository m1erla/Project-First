# Project-First

# [22,27,16,2,18,6] -> Insertion Sort

## 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[2,27,16,22,18,6] -> "2" smallest value no move (n)
[2,6,16,22,18,27] -> "6" smallest value changed second cell   (n-1)
[2,6,16,22,18,27] -> "16" smallest value no move (n-2)
[2,6,16,18,22,27] -> "18" smallest value changed four cell  (n-3)
[2,6,16,18,22,27] -> "22" smallest value no move  (n-4) 
[2,6,16,18,22,27] -> "27" last value no move  (n-5) 

## 2) Big-O gösterimini yazınız.

O(n²)
O(6²)

## 3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

"18" number is average number in this case so the number is average case.

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

## 4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

First step =>  [7,3,5,8,2,9,4,15,6] --- [2,3,5,8,7,9,4,15,6]
Second step =>  [2,3,5,8,7,9,4,15,6] --- [2,3,4,8,7,9,5,15,6]
Third step =>  [2,3,4,8,7,9,5,15,6] --- [2,3,4,5,7,9,8,15,6]
Fourth step =>  [2,3,4,5,7,9,8,15,6] --- [2,3,4,5,6,9,8,15,7]
