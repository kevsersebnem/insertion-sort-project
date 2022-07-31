# insertion-sort-project

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Questions:

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Answers:
1. Dizideki elemanların değerleri tek tek okunur en küçük olan eleman 1. sıradaki elemanla yer değiştirir. ( Örneğin 2 elemanı ile 22 elemanı) daha sonrasında dizinin en küçük elemanı ile 2. sıradaki elemanı arasında aynı işlem tekrar eder. Elemanlar soldan sağa en küçükten büyüğe doğru sıralanana kadar işlem tekrarlanır.
1.adım 2,27,16,22,18,6
2.adım 2,6,16,22,18,27
3.adım 2,6,16,18,22,27

2. O(n²)

3.
Time Complexity
 Average case: n²         Worst case: n²          Best case: n

4.Dizinin elemanlarını en küçükten büyüğe doğru sıraladığımızda 18, 3. eleman olduğu için average case deriz (dizinin ortasında kalmış olur).

5.    Birinci adım :[2,3,5,8,7,9,4,15,6]
      İkinci adım  :[2,3,4,8,7,9,5,15,6]
      Üçüncü adım  :[2,3,4,5,7,9,8,15,6]
      Dördüncü adım:[2,3,4,5,6,9,8,15,7]

Patika hesabım: https://app.patika.dev/kevsersebnem








