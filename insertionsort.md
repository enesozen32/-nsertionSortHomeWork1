{22,27,16,2,18,6} -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazalım.

insertion sort-> En basit sorting algoritmalarından biridir. Verilen örüntüden en küçük elemanı bulup en baştaki ile yer değiştiriyor. Süreç böyle devam ediyor fakat baktınki 4. sırada zaten en küçük eleman var ona dokunma 5. en küçükten devam devam et.

Başlangıç: {22,27,16,2,18,6}

1.aşama: {2,27,16,22,18,6}

2.aşama: {2,6,16,22,18,27}

3.aşama: {2,6,16,18,22,27}

Big-O gösterimi
---  Big-O (n²)  ---

Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması. 
18 sayısı Average case'dir.

{7,3,5,8,2,9,4,15,6} dizisinin Insertion Sort'a göre ilk 4 adımı.

Başlangıç: {7,3,5,8,2,9,4,15,6}

1.aşama: {2,3,5,8,7,9,4,15,6}

2.aşama: {2,3,4,8,7,9,5,15,6}

3.aşama: {2,3,4,5,7,9,8,15,6}

4.aşama: {2,3,4,5,6,9,8,15,7}

[Patika.Dev] (https://app.patika.dev/enesozenn)
