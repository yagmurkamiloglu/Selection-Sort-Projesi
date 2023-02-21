#INSERTION SORT:

 [22,27,16,2,18,6] -> Insertion Sort

   A)Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

     1) Verilen diziye ait en küçük eleman (2) bulunur ve en baştaki
      eleman ile yer değiştirir.

      [2,27,16,22,18,6]

     2) Aynı mantıkla yine dizinin ikinci en küçük elemanı (6) bulunur
      ve ikinci sıradakii eleman ile yer değiştirir.

      [2,6,16,22,18,27]

     3) Üst aşamalardaki gibi, bu sefer de dizinin üçüncü en küçük elemanı
      (16) bulunur ve üçüncü sıradaki eleman ile yer değiştirir.

      [2,6,16,22,18,27]

       Görüldüğü üzere bu aşamada bir yer değişimi olmamıştır. Bunun sebebi
      üçüncü en küçük elemanımızın zaten üçüncü sırada yer almasıdır.

     4) Bu aşamada da dizinin dördüncü en küçük elemanı (18) bulunup dördüncü
      sıradaki eleman ile yerleri değiştirilir.
       
      [2,6,16,18,22,27]

       Böylelikle istediğimiz gibi insertion sort yöntemiyle sıralı bir dizi
      elde etmiş oluruz.

   B) Big-O gösterimini yazınız.
     
     O(n^2)

   C)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki hangi case kapsamına girer? Yazınız
     (Average case: Aradığımız sayının ortada olması.
      Worst case: Aradığımız sayının sonda olması.
      Best case: Aradığımız sayının dizinin en başında olması.)

      18 sayısı, sıraladığımız dizinin dördüncü elemanıdır. Bu da, dizimizin ortasında olduğu için
     Average Case kapsamına girer.



