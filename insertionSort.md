Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]

[22,16,27,2,18,6] [16,22,27,2,18,6]

[16,22,27,2,18,6] [16,22,2,27,18,6] [16,2,22,27,18,6] [2,16,22,27,18,6] 

[2,16,22,27,18,6] [2,16,22,18,27,6] [2,16,18,22,27,6] 

[2,16,18,22,27,6] [2,16,18,22,6,27] [2,16,18,6,22,27] [2,16,6,18,22,27] [2,6,16,18,22,27] 

2.Big-O gösterimini yazınız.
O(n^2)

3.Time Complexity:
Worst case:n/2
Average case: n*2
Best case: n

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Average Case


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.Adım : [7,3,5,8,2,9,4,15,6] 

2.Adım : [3,7,5,8,2,9,4,15,6] 

3.Adım : [3,5,7,8,2,9,4,15,6] 

4.Adım : [7,3,5,2,8,9,4,15,6] 