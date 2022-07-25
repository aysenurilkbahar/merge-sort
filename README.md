## Proje 2  (Merge sort) www.patika.dev

[16,21,11,8,12,22] 

Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.

     [16,21,11]            [8,12,22]
  [16,21]   [11]        [8,12]    [22]
  [16]  [21]  [11]      [8] [12]  [22]
  [16,21]   [11]        [8,12]    [22]
    [11,16,21]            [8,12,22]
           [8,11,12,16,21,22]
           
Big-O gösterimini yazınız.

  2^x=n ise logn ve bu işlem n kez yapıldığından n.logn yani O(n.logn)
