# binarySearchTree-odev3

 # Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.


  ## Cevaplar 
[7  5  1  8  3  6  0  9  4  2]

root = 7 // 
* ilk olarak 7 rakamından başlayalım bunun root olduğunu düşünerek en başa yerleştirelim 
  daha sonra ikinci rakama geçelim. 

* ikinci rakam ilk rakam olan 7'ye bağlı olmak durumunda.
* 5 7'den küçük bir rakam bundan dolayı 7'nin solunda olmalı.
* Üçüncü rakamımız ise 1  7'den küçük bundan dolayı sola geçmeli
                 
                        7
                    5       
                1    
             
*  Dördüncü rakamımız 8 root'dan büyük olduğundan onu sağa alıyoruz.           

                 
                        7
                    5       8 
                1  

*  Beşinci rakamımız  3 bu rakam root'umuz 7'den küçük bundan dolayı solda yer almakta
    5 'ten de küçük fakat 1'den büyük olduğundan 1'in sağında yer almalı.

                     
                        7
                    5       8 
                1 
                    3   

* Altıncı rakamımız 6 root'tan küçük solda yer alacak fakat 5'ten büyük bundan dolayı 5'in sağında yer almalı.                    


                     
                     7
                5         8 
                    6
            1 
                    3  

* Yedinci rakam 0, 7'den 5'ten ve 1'den küçük olduğundan onu 1 in soluna alıyoruz.   

                     
                     7
                5         8 
                    6
            1 
        0       3  

* Sekizinci rakam 9 olduğundan 7'nin sağında ve 8'den de büyük olduğundan onunda sağına gelmiş oluyor.


                     
                     7
                5         8 
                    6           9
            1 
        0       3  

* Dokuzuncu rakamımız 4, 7nin solunda 5'ten küçük olduğundan onunda solunda fakat 1'den büyük olduğundan onun sağında 3'ten de büyük olduğundan kendisini yine  3'ün sağına alıyoruz.

                     7
                5         8 
                    6           9
            1 
        0       3  
                    4
* Son rakamımız ise 2, 2 rakamı 7'den ve 5'ten küçük bu yüzden bu rakamların solunda
  1 rakamından büyük onun sağına geçmeli 3 rakamından ise küçük bu yüzden yer alacağı konum 3'ün solu olmalı.
    
                    7
                5         8 
                    6           9
            1 
        0       3  
            2       4
