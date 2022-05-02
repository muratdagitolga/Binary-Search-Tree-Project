# Binary-Search-Tree-Project
Veri Yapıları ve Algoritmalar dersi binary search tree projesi cevapları

SORU-1
Dizinin ilk elemanı root olarak kabul edilir ROOT = 7
İkinci elaman 5 olduğu için ve root değerinden küçük olduğu için rootun SOLUNDA yer almalıdır.
Üçüncü elaman 1 olduğu için öncelikle root değeriyle karşılaştırılır küçük olduğu için soluna atanmalıdır ancak rootun solunda 5 olduğu için bu değer ile karşılaştırılır 1 değeri bu değerden de küçük olduğu için 5 in SOLUNA atanır.
Dördüncü elaman 8 olduğu için öncelikle root değeriyle karşılaştırılır değer roottan büyük olduğu için SAĞINA atanır.
Beşinci elaman 3 olduğu için öncelikle root değeriyle karşılaştırılır küçük olduğu için soluna atanmalıdır ancak rootun solunda 5 olduğu için bu değer ile karşılaştırılır. 3 değeri 5 ten küçük olduğu için soluna atanmalıdır ancak 5 in soluna daha önce 1 atandığı için 3 değeri bu değer ile karşılaştırılır. 3 değeri 1 değerinden büyük olduğundan 1 in SAĞINA atanır
Altıncı elaman 6 olduğu için öncelikle root değeriyle karşılaştırılır küçük olduğu için soluna atanmalıdır ancak rootun solunda 5 olduğu için bu değer ile karşılaştırılır. 6 değeri 5 ten büyük olduğu için sağına atanır.
Yedinci elaman 0 olduğu için öncelikle root değeriyle karşılaştırılır küçük olduğu için soluna atanmalıdır ancak rootun solunda 5 olduğu için bu değer ile karşılaştırılır. 0 değeri 5 ten küçük olduğu için soluna atanmalıdır ancak 5 in soluna daha önce 1 atandığı için 0 değeri bu değer ile karşılaştırılır. 0 değeri 1 değerinden küçük olduğundan 1 in SOLUNA atanır
Sekizinci elaman 9 olduğu için ve root değerinden büyük olduğu için rootun SAĞINA atanmalıdır ancak rootun sağında 8 olduğu için bu değer ile karşılaştırılır. 9 değeri 8 den büyük olduğu için SAĞINA atanmalıdır.  
Dokuzuncu elaman 4 olduğu için öncelikle root değeriyle karşılaştırılır küçük olduğu için soluna atanmalıdır ancak rootun solunda 5 olduğu için bu değer ile karşılaştırılır. 4 değeri 5 ten küçük olduğu için soluna atanmalıdır ancak 5 in soluna daha önce 1 atandığı için 4 değeri bu değer ile karşılaştırılır. 4 değeri 1 değerinden büyük olduğundan 1 in SAĞINA atanmalıdır ancak bu alana daha öne 3 atanmış durumda olduğundan 4 değeri ile 3 değeri karşılaştırılır. 4 değeri 3 ten büyük olduğundan 3 ün SAĞINA atanır.
Onuncu elaman 2 olduğu için öncelikle root değeriyle karşılaştırılır küçük olduğu için soluna atanmalıdır ancak rootun solunda 5 olduğu için bu değer ile karşılaştırılır. 2 değeri 5 ten küçük olduğu için soluna atanmalıdır ancak 5 in soluna daha önce 1 atandığı için 2 değeri bu değer ile karşılaştırılır. 2 değeri 1 değerinden büyük olduğundan 1 in SAĞINA atanmalıdır ancak bu alana daha öne 3 atanmış durumda olduğundan 2 değeri ile 3 değeri karşılaştırılır. 2 değeri 3 ten küçük olduğundan 3 ün SOLUNA atanır ve süreç tamamlanır.

Sonuç olarak * işaretini bağlantı noktası olarak düşünürsek tree şekli şu şekilde olacaktır:

                                  7
                                *  *
                               5    8
                              * *    *
                             1   6    9
                            * *
                           0   3
                              * *
                             2   4
