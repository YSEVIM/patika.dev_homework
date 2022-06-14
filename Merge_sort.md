# Merge Short Projet
## Proje 2

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.
  
                    [16,21,11,8,12,22]
               [16,21,11]         [8,12,22]
         [16,21]      [11]     [8,12]       [22]
      [16]     [21]     [11]     [8]     [12]     [22]
         [16,21]      [11]     [8,12]       [22]
               [11,16,21]         [8,12,22]
                     [8,11,12,16,21,22]

* Sorgu sayısı n-1. n dominant faktör bu yüzden big-o notaion O(n)

* İşlem her seferinde yarıya iniyor (2^x=n) -> (logn=x) big-o notain O((logn))

* Time comlexity = O((nlogn))
