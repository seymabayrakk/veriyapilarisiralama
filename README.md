# Kodluyoruz Sıralama Algoritmaları

## Proje1:

[22,27,16,2,18,6]-> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

-  2  27  16  22  18  6

-	2   6   16  22  18  27

-	2  6  16  22  18   27

-	2   6   16  18  22  27

   

2. Big-O gösterimini yazınız.  o(n^2)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- Average case: n/2 işlem

- Worst case: n işlem

- Best case: Tek işlem

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. Avarage case'e girer

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

   ​                

   

## Proje2:

​                   [16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

-16        21         11       8         12        22 

​		[16,21,11]                      [8,12,22] 

​	[16,21]    	[11]               [8,12]         [22] 

​	[16,21]    	[11]  			    [8,12]         [22] 

​	 [11,16,21] 							    [8,12,22] 

​					[8,11,12,16,21,22]

- Big-O gösterimini yazınız.

  On( log n)

  

  ##  Proje 3:

  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

  - **Root: 7**

​										7

​								5				8

​							/     \           \

​                       1            6            9

​                      /   \      

​                   0       3

​                  /   \

​               2       4