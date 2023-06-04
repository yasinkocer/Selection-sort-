[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.



[22, 27, 16, 2, 18, 6]    
[2, 27,16,22,18,6]  2 ve 22 nin yeri değişti
[2,6,16,22,18,27]  6 ve 27 nin yeri değişti
([2,6,16,22,18,27]   16 olması gerektiği yerde olduğu için işleme devam edildi)
[2,6,16,18,22,27]  18 ve 22 nin yeri değişti sonra kontrol etti ve hepsi sıralı olduğu için işlem bitti 
n+(n-1)+(n-2)+….+1 = n.(n+1)/2 = n2 +n  /2 den Big-O  O(n2) olur 


[2,6,16,18,22,27] 18 sayısının ortada olmasından dolayı Average case olur.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[7,35,8,2,9,4,15,6] 
[2,35,8,7,9,4,15,6]  ilk adım 2 ve 7 nin yeri değişti
[2,4,8,7,9,35,15,6]  ikinci adım 4 ve 35 in yeri değişti 
[2,4,6,7,9,35,15,8]  üçüncü adım 6 ve 8 in yeri değişti 
[2,4,6,7,9,35,15,8]  dördüncü adımda 7 kontrol edildi ve yerinde bir değişiklik olmadı 

