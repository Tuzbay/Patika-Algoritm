# Patika-Algoritm
Patikadaki "Veri Yapıları ve Algoritmalar" modül Ödevleri 

[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.
3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---- ---- ---- ---- ---- ---- 

1.

[22,27,16,2,18,6] -- 1. Aşama
[22,27|,16,2,18,6] -- 2. Aşama
[16,22,27|,2,18,6] -- 3. Aşama
[2,16,22,27|,18,6] -- 4. Aşama
[2,16,18,22,27|,6] -- 5. Aşama
[2,6,16,18,22,27|] -- 6. Aşama

2.

Best case : O(n)
Average case : O (n^2)
Worst Case : O(n^2)

3.

Dizi sıralandıktan sonra 18 sayısı ortada bulunur. Average Case kapsamına girmektedir. 

4.

[7|,3,5,8,2,9,4,15,6] -- 1.Aşama
[3,7|,5,8,2,9,4,15,6] -- 2.Aşama
[3,5,7|,8,2,9,4,15,6] -- 3.Aşama
[3,5,7,8|,2,9,4,15,6] -- 4.Aşama




