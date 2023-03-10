# Selection-Sort-Projesi-Patika
patika.dev Selection Sort

Insertion Sort aşamaları:

- [22, 27, 16, 2, 18, 6] - İlk eleman zaten sıralı olduğundan, yer değiştirme yapmadan devam ediyoruz.
- [22, 27, 16, 2, 18, 6] - İkinci eleman olan 27, ilk elemandan daha büyük olduğu için yer değiştirme yapmıyoruz.
- [16, 22, 27, 2, 18, 6] - Üçüncü eleman olan 16, ilk iki elemandan daha küçük olduğu için yer değiştiriyoruz.
- [2, 16, 22, 27, 18, 6] - Dördüncü eleman olan 2, daha önceki elemanların hepsinden daha küçük olduğu için sıralanmış dizinin en başına yerleştiriyoruz.
- [2, 16, 18, 22, 27, 6] - Beşinci eleman olan 18, kendinden önceki elemanlardan daha küçük olduğu için 2 ve 16'nın arasına yerleştiriyoruz.
- [2, 6, 16, 18, 22, 27] - Altıncı eleman olan 6, kendinden önceki elemanlardan daha küçük olduğu için sıralanmış dizinin en başına yerleştiriyoruz.

- Big-O gösterimi: O(n^2)

- 18 sayısı için Time Complexity: Average Case

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
[7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection Sort aşamaları:

- [2, 3, 5, 8, 7, 9, 4, 15, 6] - Dizideki en küçük eleman olan 2, dizinin başındaki elemanla yer değiştiriliyor.
- [2, 3, 5, 8, 7, 9, 4, 15, 6] - Dizideki ikinci en küçük eleman olan 3, ikinci sıradaki elemanla yer değiştiriliyor.
- [2, 3, 4, 8, 7, 9, 5, 15, 6] - Dizideki üçüncü en küçük eleman olan 4, dizinin üçüncü sırasındaki elemanla yer değiştiriliyor.
- [2, 3, 4, 5, 7, 9, 8, 15, 6] - Dizideki dördüncü en küçük eleman olan 5, dizinin dördüncü sırasındaki elemanla yer değiştiriliyor.
