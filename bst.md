# BinarySearchTree
Binary Search Tree

# Proje 3 
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


# Cevap

Dizinin en başındaki eleman root olarak seçilir. Bu dizideki root 7 olacaktır.

5, 7'den küçük olduğu için 7'nin soluna gelir.

1, 7'den küçük olduğu için 7'nin soluna gelir. Daha sonra 5 elemanından küçük olduğu için yeni bir bağ ile sol tarafa yerleştirilir.

8, 7'den büyük olduğu için 7'nin sağına geçer.

3, 7'den küçük olduğu için sola, 5 elemanından küçük olduğu için sola, 1'den ise büyük olduğu yeni bir bağ ile sağa gelir.

6, 7'den küçük olduğu sola, 5'den büyük olduğu için yeni bir bağ ile sağ tarafa geçer.

0, 7'den küçük olduğu için sola, sırasıyla 1'e kadar gelir. 1'den küçük olduğu için sol tarafa yerleştirilir.

9, 7'den büyük olduğu için sağa, 8'den büyük olduğu için sağına geçer.

4, 7'den küçük olduğu için sola gelerek 3 elemanının sağına gelir.

2, 7'den küçük olduğu için sola ve sırasıyla takip ederek 3 elemanının soluna yerleştirilir.



                       7
                     (root)

                5                8
          
            1         6               9
        
        0      3 

            2       4
