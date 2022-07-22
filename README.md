# Insertion-Sort-Projesi
Insertion-Sort Bitirme Projesi

[22,27,16,2,18,6] -> Insertion Sort

1-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2-Big-O gösterimini yazınız.

3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

#1-Aşamalar:

(n) [22,27,16,2,18,6]

(n-1) [2,27,16,22,18,6]

(n-2) [2,6,16,22,18,27]

(n-3) [2,6,16,22,18,27]

(n-4) [2,6,16,18,22,27]

(n-5) [2,6,16,18,22,27]

(n-6) [2,6,16,18,22,27] Aslında 3. aşamada bitmesine karşın bunu bilemeyeceğimiz için devam ettirdik.

#2-Big O Gösterimi:

Worst Case: O(n²) = n*(n+1)/2=>n^2 baskın sonuç

Average Case: O(n²)

Best Case: O(n)

#3-Time Complexity:

Worst Case:[27,22,18,16,6,2]

Best Case:[2,6,16,18,22,27]

Average Case:[18,22,27,2,6,16]

#4-"18" Sayısının Durumu:

Tam olarak ortada bulunur.

#5-Sıralama:

0-[7,3,5,8,2,9,4,15,6]

1-[2,3,5,8,7,9,4,15,6]

2-[2,3,5,8,7,9,4,15,6]

3-[2,3,4,8,7,9,5,15,6]

4-[2,3,4,5,7,9,8,15,6]

5-[2,3,4,5,6,9,8,15,7]

6-[2,3,4,5,6,7,8,15,9]

7-[2,3,4,5,6,7,8,15,9]

6-[2,3,4,5,6,7,8,9,15]
