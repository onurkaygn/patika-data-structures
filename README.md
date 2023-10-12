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
