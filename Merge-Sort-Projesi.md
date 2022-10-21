# Proje 2
[Patika.dev](https://www.patika.dev)

## [16,21,11,8,12,22] -> Merge Sort

## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
1)Liste parçaya ayrılır.
                                16,21,11,8,12,22
                    16,21,11                        8,12,22
2)Liste parçaya ayrılır.
                                16,21,11,8,12,22
                    16,21,11                        8,12,22
        16,21   11                                           8,12    22
3)Liste parçaya ayrılır.
                                16,21,11,8,12,22
                    16,21,11                        8,12,22
        16,21   11                                           8,12    22
16          21          11                              8        12        22
4)Liste küçükten büyüğe olacak şekilde tekrardan sıralanır.
                                16,21,11,8,12,22
                    16,21,11                        8,12,22
        16,21   11                                           8,12    22
16          21          11                              8        12        22
        16,21   11                                           8,12    22
5)Liste küçükten büyüğe olacak şekilde tekrardan sıralanır.
                                16,21,11,8,12,22
                    16,21,11                        8,12,22
        16,21   11                                           8,12    22
16          21          11                              8        12        22
        16,21   11                                           8,12    22
                    11,16,21                        8,12,22
6)Liste küçükten büyüğe olacak şekilde tekrardan sıralanır.
                                16,21,11,8,12,22
                    16,21,11                        8,12,22
        16,21   11                                           8,12    22
16          21          11                              8        12        22
        16,21   11                                           8,12    22
                    11,16,21                        8,12,22
                                8,11,12,16,21,22
 Toplam 6 aşamadan oluşmuş oldu. Listenin son hali [8,11,12,16,21,22] şeklinde oldu.
## Big-O gösterimini yazınız.
O(nlogn).
