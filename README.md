# Merge-Sort-Projesi
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Merge Sort

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

I. Aşama:
Başlangıç dizisi [16,21,11,8,12,22] olarak verilir.
Dizi 2 eşit parçaya bölünür: [16,21,11] ve [8,12,22].

II. Aşama:
Başlangıç dizisi [16,21,11,8,12,22] olarak verilir.
Dizi 2 eşit parçaya bölünür: [16,21,11] ve [8,12,22].

III. Aşama:
[21,11] -> [21], [11]
[12,22] -> [12], [22]

IV. Aşama: 
Şimdi alt diziler birleştirilmeye başlanır:
[16], [21], [11], [8], [12], [22]

V. Aşama:
İkişerli gruplar halinde sıralanır:
[16,21], [8,11], [12,22]

VI. Aşama:
Tüm diziler birleştirilir:
[8,11,16,21,12,22]

Sonuç olarak  [8,11,12,16,21,22] elde edilir.

Big-O gösterimini yazınız.
--> Big-O gösterimi O(nlogn) şeklindedir.




