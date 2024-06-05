# Insertion Sort

[22, 27, 16, 2, 18, 6] dizinin sırasız hali

Her adımda “|” işareti, sıralanmış kısmı ve sıralanmamış kısmı ayırır. Her adımda, sıralanmamış kısmın ilk elemanı, sıralanmış kısmın uygun yerine eklenir. Bu işlem, sıralanmamış kısım boş kalana kadar devam eder.

[22 | 27, 16, 2, 18, 6] --- 

[22, 27 | 16, 2, 18, 6] --- 

[16, 22, 27 | 2, 18, 6] ---

[2, 16, 22, 27 | 18, 6] ---

[2, 16, 18, 22, 27 | 6] ---

[2,  6, 16, 18, 22, 27] ---

İnsertion Sort algoritmasının zaman karmaşıklığı, en kötü durumda O(n²), en iyi durumda ise O(n)’dir.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı Average Case durumuna girer çünkü aradığımız sayı dizinin ortasındadır.

# Selection Sort

**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımı:

1. Adim: [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. Adim: [2, 3, 4, 8, 7, 9, 5, 15, 6]
3. Adim: [2, 3, 4, 5, 7, 9, 8, 15, 6]
4. Adim: [2, 3, 4, 5, 6, 9, 8, 15, 7]