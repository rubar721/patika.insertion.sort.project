# patika.insertion.sort.project
project 1

[22,27,16,2,18,6]

1-) insertion sort aşamaları;
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]

2-)big-O gösterimi;
=n+(n-1)+(n-2)+---------+1
=(n*(n+1)/2)
=(n^2+n)/2
dominant Big-O notation;
O(n^2)

3-)time complexity;
-> best case= O(n^2)
-> average case= O(n^2)
-> worst case= O(n^2)

4-) n(18)=5'tir.
1<=5<=6 ara değer olduğundan average case'e girer.

->[7,3,5,8,2,9,4,15,6] dizisinin insertion sort'a göre ilk 4 adımı;

[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
