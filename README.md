# veri-yap-lar-ve-algoritmalar

insertion sort, merge sort , binary search tree projeleri


[22,27,16,2,18,6] -> Insertion Sort

1. [2,27,16,22,18,6]
2. [2,6,16,22,18,27]
3. [2,6,16,18,22,27]

O(n²)
average case

[7,3,5,8,2,9,4,15,6]  -> Insertion Sort

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
5. [2,3,4,5,6,7,8,15,9]
6. [2,3,4,5,6,7,8,9,15]




[16,21,11,8,12,22] -> Merge Sort

    [16,21,11,8,12,22]

    /                 \

    [16,21,11]         [8,12,22]

    /       \           /      \

    [16]      [21,11]      [8]     [12,22]

    /          /    \       /        /   \

    [16]       [21]   [11]  [8]      [12]  [22]

    \          \     /      \        \    /

    [16]       [11,21]       [8]     [12,22]

    \          /            \        /

    [11,16,21]             [8,12,22]

    \                     /

    [8,11,12,16,21,22]

O(nlogn)





[7,5,1,8,3,6,0,9,4,2] -> Binary-Search-Tree

    5
                                 /
                               2       7
                              / \      /
                             1   4    6   8
                            /   /
                           0   3            9

root 5'tir. rootun solunda rootttan küçükler, sağında rootttan büyükler vardır.
örneğin 8 rakamına ulaşmak için 5'e bakıyoruz. 5ten büyük olduğu için sağ tarftan devam ediyoruz. 8, 7den büyük olduğu için tekrar sağdan devam ediyoruz. ve 8e ulaştık.
