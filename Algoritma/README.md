# Selection/İnsertion Sort
<h2>Soru 1</h2>

[22,27,16,2,18,6]
a- Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.

b- Big-O gösterimini yazınız.

c- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
- Average Case: Aranan sayının ortada olması
- Worst Case: Aranan sayının sonda olması
- Best Case: Aranan sayının dizinin en başında olması

Cevap-a

1.Adım [22, 27, 16, 2, 18, 6]

2.Adım [22, 27, 16, 2, 18, 6] (22 sabit, 27'yi ileri al)

3.Adım [16, 22, 27, 2, 18, 6] (16'yı doğru konuma yerleştir)

4.Adım [2, 16, 22, 27, 18, 6] (2'yi doğru konuma yerleştir)

5.Adım [2, 16, 18, 22, 27, 6] (18'i doğru konuma yerleştir)

6.Adım [2, 6, 16, 18, 22, 27] (6'yı doğru konuma yerleştir)

Cevap-b

   1.Adım: 1

   2.Adım: 2

   3.Adım: 3

    .
    .
    Son Adım: n

    Özet: (n*(n+1)/2) --> O(n^2)

Cevap-c

    Worst case

# Merge Sort
<p>
[16,21,11,8,12,22]
a- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Cevap a 

1.Adım[16, 21, 11, 8, 12, 22]

2.Adım[16, 21, 11, 8, 12, 22] (16 sabit, 21'i ileri al)

3.Adım[11, 16, 21, 8, 12, 22] (11'i doğru konuma yerleştir)

4.Adım[8, 11, 16, 21, 12, 22] (8'i doğru konuma yerleştir)

5.Adım[8, 11, 12, 16, 21, 22] (12'yi doğru konuma yerleştir)

6.Adım[8, 11, 12, 16, 21, 22] (22 sabit)


b- Big-O gösterimini yazınız.

Cevap-b

    O(nlogn)
</p>

# Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
a- Yukarıda verilen dizinin Binary-Search-Tree aşamalarını yazınız.

Cevap-a

           7
          / \
         5   8
        / \   \
       1   6   9
      / \     /
     0   3   9
        / \
       2   4
