# Merge-Sort

[16,21,11,8,12,22] -> Merge Sort

   Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

    Aşama 1  : [16,21,11] - [8,12,22]
    Aşama 2  : [16] - [21,11] - [8,12] - [22]
    Aşama 3  : [16] - [21] - [11] - [8] - [12] - [22]
    Aşama 4  : [16] - [11,21] - [8,12] - [22]
    Aşama 5  : [11,16,21] - [8,12,22]
    Aşama 6  : [8,11,12,16,21,22]
 
  Big-O gösterimini yazınız.

   n adet aşama vardır ve Her aşamada örüntüyü ikiye böleriz. 2^x = n, x = logn
   Big-O : O(nlogn)
