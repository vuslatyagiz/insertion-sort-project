# insertion-sort-project
proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6] -> dizimiz
1. [22,27,16,2,18,6]
2. [16,22,27,2,18,6]
3. [2,16,22,27,18,6]
4. [2,16,18,22,27,6]
5. [2,6,16,18,22,27]

Big-O gösterimini yazınız.

Worst Case: O(n^2)  
Average Case: O(n^2)  
Best Case: O(n)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Dizide çok fazla kaydırma yapılmadığından ve 18 ortada olduğu için average case'e girer.

Average case: Aradığımız sayının ortada olması.
Worst case: Aradığımız sayının sonda olması.
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. adım en küçük eleman 2 olduğu 2 ile 7 yer değiştirir. [2,3,5,8,7,9,4,15,6]
2. 3'ün yeri doğru olduğu için yer değiştirmez. [2,3,5,8,7,9,4,15,6]
3. 5 > 4 olduğu için yer değiştirir. [2,3,4,8,7,9,5,15,6]
4. kalan kısım [8,7,9,5,15,6] olduğu için 5 ile 8 yer değiştirir. [2,3,4,5,7,9,8,15,6] olur.
