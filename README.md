# Patika Veri Yapıları ve Algoritmalar

## [22,27,16,2,18,6] -> Insertion Sort

1: [22], [27, 16, 2, 18, 6]

2: [22, 27], [16, 2, 18, 6]

3: [16, 22, 27], [2, 18, 6]

4: [2, 16, 22, 27], [18, 6]

5: [2, 16, 18, 22, 27], [6]

6: [2, 6, 16, 18, 22, 27], []

### Big O Gösterimini Yazınız

1+(n-5)+(n-4)+(n-3)+(n-2)+(n-1)+n=[n(n+1)]/2=(n^2+n)/2 => O(n^2)

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

Average.

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1 : [2, 3, 5, 8, 7, 9, 4, 15, 6]

2: [2, 3, 5, 4, 7, 9, 8, 15, 6]

3: [2, 3, 4, 5, 7, 6, 8, 15, 9]

4: [2, 3, 4, 5, 6, 7, 8, 15, 9]

## [16,21,11,8,12,22] -> Merge Sort

1 : [16, 21, 11], [8, 12, 22]

2: [16], [21, 11], [8], [12, 22]

3: [16], [11, 21], [8], [12, 22]

4: [11, 16, 21], [8], [12, 22]

5: [11, 16, 21], [8, 12, 22]

6: [8, 11, 12, 16, 21, 22]

### Big-O gösterimini yazınız.

O(nlogn)

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root = 7

1: 7 > 5 bu yüzden 7'nin soluna ekle.

2: 7 > 1 & 5 > 1 bu yüzden 5'in soluna ekle.

3: 8 > 7 bu yüzden 7'nin sağına ekle.

5: 7 > 3 & 5 > 3 & 1 < 3 bu yüzden 1'in sağına ekle.

6: 7 > 6 & 5 < 6 bu yüzden 7'nin soluna 5'in sağına ekle.

7: 7 > 0 & 5 > 1 & 1 > 0 bu yüzden 7'nin soluna git 5'in soluna git 1'in soluna ekle.

8: 7 < 9 & 8 < 9 bu yüzden 8'in sağına ekle.

9 : 7 > 4 & 5 > 4 & 4 > 1 & 4 > 3 bu adımlar sonucu 3'ün sağına ekle.

10 : 7 > 2 & 5 > 2 & 2 > 1 & 3 > 2 3'ün soluna ekle.

             7
            / \
           5   8
          / \   \
         1   6   9
        / \
       0   3
          / \
         2   4
