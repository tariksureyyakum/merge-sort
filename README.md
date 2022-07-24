[16,21,11,8,12,22] -> Merge Sort

<strong>1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.</strong>
<strong>2) Big-O gösterimini yazınız.</strong>
<hr>
Answers;
<hr>
1
[16,21,11,8,12,22] dizi ikiye bölünür.
[16,21,11] - [8,12,22]
[16,21] - [11] and [8,12] - [22]
[16] [21] - [11] ve [8] [12] - [22] yalnız bıraktığımız veriler küçükten büyüğe olucak şekilde kendi grupları arasında birleştirilir.
[11,16,21] ve [8,12,22] sona kalan iki grup küçükten büyüğe olucak şekilde birleştirilir.
[8,11,12,16,21,22]
<hr>
2
Worst Case: O(nlogn)
Average Case: O(nlogn)
Best Case: O(nlogn)