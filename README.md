# Veri-Yap-lar-ve-Algoritmalar-Merge-Sort-Projesi
Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Merge sort algoritması yapıyı ikiye böler ve her parçayı ayrı ayrı sıralar.Daha sonra iki sıralı parçayı tekrar birleştirir ve sonuç olarak sıralı bir dizi elde eder.

-Dizi [16, 21, 11, 8, 12, 22] ilk olarak ikiye bölünür ve [16, 21, 11] ve [8, 12, 22] parçaları oluşur.

-Her parça ayrı ayrı sıralanır. Örneğin, [16, 21, 11] parçası sıralandığında [11, 16, 21] oluşur. [8, 12, 22] parçası sıralandığında [8, 12, 22] oluşur.

-İki sıralı parça [11, 16, 21] ve [8, 12, 22] birleştirilir ve [8, 11, 12, 16, 21, 22] oluşur.

Big-O gösterimini yazınız.

-O(n*log(n))
