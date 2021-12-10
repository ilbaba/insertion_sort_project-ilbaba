# insertion_sort_project-ilbaba
Insertion Sort Projesi - Patika - Ilgar Babashli
* [22,27,16,2,18,6] -> Insertion Sort
# _Q1_ 
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
# _Ans_

1) [22,27,16,2,18,6] --> n

2) [2,27,16,22,18,6] --> n-1

3) [2,6,16,22,18,27] --> n-2

4) [2,6,16,18,22,27] --> 1

# _Q2_
Big-O gösterimini yazınız.
# _Ans_
n+(n-1)+(n-2)+ ... + 1 = (n^2+n)/2

Big O Notation: O(n^2)
# _Q3_
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
# _Ans_

Sıralamanın artan şekilde yapıldığını varsayarsak, aşağıdaki sayıları aradığımız takdirde oluşan time complexity'ler şöyledir:

Average Case: 16 veya 18 

Worst Case: 27

Best Case: 2

# _Q4_
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
# _Ans_
Average Case

# _Q5_
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
# _Ans_
[7,3,5,8,2,9,4,15,6] - 1. Aşama (n)

[2,3,5,8,7,9,4,15,6] - 1. Aşama (n-1)

[2,3,4,8,7,9,5,15,6] - 1. Aşama (n-2)

[2,3,4,5,7,9,8,15,6] - 1. Aşama (n-3)

